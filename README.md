# `react native`源码编译

> https://github.com/facebook/react-native/commit/9d71b166a6c9d9afec7186c6a33aedc6975aa43c

修复android多实例切换时，因线程导致的闪退问题，如：

* Error while updating property '??' of a view managed by: ??
* Error while updating property '??' in shadow node of type: ??


## 环境

* java 1.8.xx
* android studio

## 编译

* `./gradlew :ReactAndroid:installArchives --no-daemon`