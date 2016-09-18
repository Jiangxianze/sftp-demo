SFTP介紹：<br>
	sftp是Secure File Transfer Protocol的缩写，安全文件传送协议。可以为传输文件提供一种安全的加密方法。sftp 与 ftp 有着几乎一样的语法和功能。<br>
	SFTP 为 SSH的一部分，是一种传输档案至 Blogger 伺服器的安全方式。其实在SSH软件包中，已经包含了一个叫作SFTP(Secure File Transfer Protocol)的安全<br>
	文件传输子系统，SFTP本身没有单独的守护进程，它必须使用sshd守护进程（端口号默认是22）来完成相应的连接操作，所以从某种意义上来说，SFTP并不像一个服务器程序，<br>
	而更像是一个客户端程序。SFTP同样是使用加密传输认证信息和传输的数据，所以，使用SFTP是非常安全的。但是，由于这种传输方式使用了加密/解密技术，<br>
	所以传输效率比普通的FTP要低得多，如果您对网络安全性要求更高时，可以使用SFTP代替FTP。

JSch介紹：<br>
	JSch 是SSH2的一个纯Java实现。它允许你连接到一个sshd 服务器，使用端口转发，X11转发，文件传输等等。你可以将它的功能集成到你自己的 程序中。<br>
	同时该项目也提供一个J2ME版本用来在手机上直连SSHD服务器。