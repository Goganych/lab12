# lab12

Написать программу на *C++* обеспечивающую асинхронный запрос по заданному *URL* к *HTTPS* серверу на получение кода доступа. Для создания асинхронного запроса необходимо использовать следующие примитивы многопоточного программирования: `std::thread` для управления потоком и `std::promise` для ассинхронной обработки кода ответа.
Передача аргумента происходит через командную строку.
Пример работы программы:

## Terminal:
```ShellSession
$ ./main https://main.ru
Redirect to: https://main.ru/
Код ответа: 200
```

_Ссылки:_

```protocols:
- HTTP: https://ru.wikipedia.org/wiki/HTTP
documentaion:
- CURL library: https://curl.haxx.se/libcurl/c/
- Boost.Asio: http://www.boost.org/doc/libs/1_65_1/doc/html/boost_asio.html
hunter:
- CURL: https://docs.hunter.sh/en/latest/packages/pkg/CURL.html
- OpenSSL: https://docs.hunter.sh/en/latest/packages/pkg/OpenSSL.html
- Boost: https://docs.hunter.sh/en/latest/packages/pkg/Boost.html
examples:
- request: https://curl.haxx.se/libcurl/c/https.html
- response: https://curl.haxx.se/libcurl/c/CURLINFO_RESPONSE_CODE.html
- client: https://github.com/CloudPolis/webdav-client-cpp```
