# INSPIRCD 编译脚本说明
* 源码属于 [inspircd](https://github.com/inspircd/inspircd)
* 编译脚本属于 [inspircd-build](https://github.com/inspircd/inspircd-build)
* 版权属于原作者 InspIRCd Team <noreply@inspircd.org>; 感谢他们的付出
* 
* 编译脚本修改说明: 
* * 我们除去了rpm软件包编译，只保留了deb软件包编译;
* * 打包后的程序使用了所有模块(除去许可不兼容的模块)
* * 构建完会生成Debian和Ubuntu对应的软件包, 但是发布Release只上传Debian的软件包
* * 其他的软件包在https://github.com/ARKFUTURE/inspircd-package-builder/actions请您自取

```
声明:打包后的程序 排除了 geo_maxmind及ssl_openssl 两个模块
所以可以分发二进制文件
```
