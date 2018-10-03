# Задание 3

Отправить запросы на http://httpbin.org, проанализировать ответ и код состояния. Описать работу HTTP протокола в каждом запросе.

/ip

GET /ip HTTP/1.1

Host: httpbin.org

Accept: */*

____________________

/get

GET /get?foo=bar&1=2&2/0&error=True HTTP/1.1

Host: httpbin.org

Accept: */*

____________________

/post

POST /post HTTP/1.1

Host: httpbin.org

Accept: */*

Content-Length: вычислить длину контента и втавить сюда число!!!

Content-Type: application/x-www-form-urlencoded

foo=bar&1=2&2%2F0=&error=True

____________________

/cookies/set

GET /cookies/set?country=Ru HTTP/1.1

Host: httpbin.org

Accept: */*

____________________

/cookies

GET /cookies HTTP/1.1

Host: httpbin.org

Accept: */*

____________________

/redirect

GET /redirect/4 HTTP/1.1

Host: httpbin.org

Accept: */*
