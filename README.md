# INSPIRCD 编译脚本说明
* 源码属于 [inspircd](https://github.com/inspircd/inspircd)
* 编译脚本属于 [inspircd-build](https://github.com/inspircd/inspircd-build)
* 版权属于原作者 INSPIRCD 开发团队; 感谢他们的付出
* 
* 编译脚本修改说明: 
* * 我们除去了rpm软件包编译，只保留了deb软件包编译;
* * 打包后的程序使用了所有模块(除去许可不兼容的模块)
* * 此脚本只支持 Debian 系统;

```
声明:打包后的程序 排除了 geo_maxmind及ssl_openssl 两个模块
所以可以安全分发二进制文件
```
