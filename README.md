#### Download consul-template
wget https://releases.hashicorp.com/consul-template/0.20.0/consul-template_0.20.0_linux_amd64.zip
unzip onsul-template_0.20.0_linux_amd64.zip

#### Run command consul template 
```
./consul-template   -template="/tmp/nginx.conf.ctmpl:/etc/nginx/conf.d/default.conf"
```
