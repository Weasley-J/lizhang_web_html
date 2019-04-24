# lizhang_web_html5
A web html of www.lizahng-layer.com

web html of lizahng Build with httpd Use Note: The default directory is current DIR. 

默认发布目录： /var/www/html
默认发布文件： /var/www/html/index.html ##需自行建立

1.Download Original html files： git clone https://github.com/Weasley-J/lizhang_web_html5.git

# 2.Unzip Files： unzip ./lizhang_web_html5/lizhang.zip -d ./lizhang_web_html5/

3.Move files to superior directory: mv -f ./lizhang_web_html5/* ./ && mv -f ./lizhang_web_html5/images/index5.jpg ./images/

4.Back to /var/www/html && Set permission for dir html： cd /var/www/ && chmod 755 ./html
