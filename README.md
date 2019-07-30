#### Download consul-template
```
wget https://releases.hashicorp.com/consul-template/0.20.0/consul-template_0.20.0_linux_amd64.zip
unzip consul-template_0.20.0_linux_amd64.zip
git clone https://github.com/liwsakilive/consul-template.git
```

#### Run command consul template 
```
./consul-template   -template="/tmp/nginx.conf.ctmpl:/etc/nginx/conf.d/default.conf"
```
