# 生成KEY
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem

# 安装nginx
sudo yum install nginx

# 启动nginx
nginx -c 绝对路径.conf

