# h5
h5
- nginx配置文件添加
``
	server {
		listen       80;
		server_name  abc.com;


		location / {
			root D:\web\h5;
			index index.html;
		}


	}
``

- fiddler配置
tools-options-https:勾选decrypt https traffic
tools-options-connections:勾选allow remote computers to connect,设置fiddler listens on port 8888
tools-hosts 配置127.0.0.1 abc.com

-iphone wifi必须和电脑在同一wifi下，然后访问abc.com


