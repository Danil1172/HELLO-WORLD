# HELLO-WORLD
Подготовка
cобрать Poco
поставить cmake sudo apt-get install cmake
поставить Eclipse IDE for C/C++ Developers или любую другую IDE





Проверим работу сервера из консоли
curl localhost:5849/ping -v
Ответ должен быть 200, приблизительно таким
*   Trying 127.0.0.1...
* Connected to localhost (127.0.0.1) port 5849 (#0)
> GET /ping HTTP/1.1
> Host: localhost:5849
> User-Agent: curl/7.47.0
> Accept: */*
> 
< HTTP/1.1 200 OK
< Date: Sun, 18 Sep 2016 14:08:12 GMT
< Connection: Close
< 
* Closing connection 0
