## ReadingJDK
### jdk源码包准备：
  在安装后的jdk根目录可以找到src.zip压缩包，解压后就可以得到源码：
### 源码下各个包的说明：
1. __java.*__ ：这个是javaSE标准库，保持向后兼容。
2. __javax.*__: 这个是标准库的扩，也是标准库的一部分。
3. __com.sun.*__: 这个包下面的内容，尽量不在项目中引用，是sun的hotspot虚拟机中java.* 和javax.*的实现类。
4. __org.*__: 一些企业或者组织提供的java类库。
5. __launcher__: 是一些c源码，好像是用于找到我们程序main入口的。
