# ReverseProxy
ReverseProxy in golang

## Use:

	./ReverseProxy_[OS]_[ARCH] -h
	
	Usage of ReverseProxy_[OS]_[ARCH]:
	  -l string
	        listen on ip:port (default "0.0.0.0:8888")
	  -r string
	        reverse proxy addr (default "http://idea.lanyus.com:80")


	./ReverseProxy_windows_amd64.exe -l "0.0.0.0:8081" -r "https://www.baidu.com"

	Listening on 0.0.0.0:8081, forwarding to https://www.baidu.com

 1:下载后双击打开然后不要关闭当前窗口
 2:需要一个UUID，在网上找一个生成UUID
 3:拼接地址http://127.0.0.1:8888/UUID
 4:地址填写上面URL，然后Active
 5:修改模式为 work offline
 

