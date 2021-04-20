# nginx-redirector
Docker Based Nginx Redirector
##Docker Build Komutu
```
sudo docker build -t nginx-redirector .        
```
## Build Edilen İmajın Çalıştırılması
```
sudo docker run -it --rm -d -p 8080:80 --name web nginx-redirector  
```
