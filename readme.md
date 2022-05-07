See release

apache m1 笔记本，或者台式机设备，对于JDK的支持是残缺的，特别是如果你需要Oracle JDK 8中的一些私有API，你如果用zuul 的JDK，会面临缺失的API。
所以你就需要这个rt.jar包。因为它提供了Oracle JDK 8 等级别的api。就是从Oracle JDK x86里面抠出来的jar包，复制到相应的位置，你的java 8 就可以无痛在mac m1设备上运行了。
