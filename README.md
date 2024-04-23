# esp_http_server

This library was taken from ESP-IDF v5.2. In v5.2, async APIs were added to `esp_http_server`
that are necessary for server-sent events that [lumen](https://github.com/Lumenaries/lumen)
relies on. However, the Arduino used in `lumen` only supports ESP-IDF v5.1.
