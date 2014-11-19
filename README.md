Arduino_WebServer
=================

the official Web Server example code, just for learning and testing

Setup:
  1. Connect Arduino with the Ethernet shield
  2. Connect Arduino to router with network cable
  3. Connect computer to router with network cable
  3. Check computer's IP: ipconfig, and get result like 192.168.0.7
  4. Set the Arduino's IP as 192.168.0.177, same network segment as above
  5. Visit 192.168.0.177:80 by Firefox, which should not apply proxy

Arduino Serial output:
  new client
  GET / HTTP/1.1
  Host: 192.168.0.177
  User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64; rv:34.0) Gecko/20100101 Firefox/34.0
  Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
  Accept-Language: zh-cn,zh;q=0.8,en-us;q=0.5,en;q=0.3
  Accept-Encoding: gzip, deflate
  Connection: keep-alive
  Cache-Control: max-age=0
  
  client disconnected
  new client
  GET / HTTP/1.1
  Host: 192.168.0.177
  User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64; rv:34.0) Gecko/20100101 Firefox/34.0
  Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
  Accept-Language: zh-cn,zh;q=0.8,en-us;q=0.5,en;q=0.3
  Accept-Encoding: gzip, deflate
  Connection: keep-alive
  Cache-Control: max-age=0
  
  client disconnected
