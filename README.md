## 1 задание:
[dockerfile](..%2Fdockerfile) для сборки образа nginx с кастомной страницей приветствия
## 2 задание:

[dockerfile](stocks_products/dockerfile) для сборки образа с django приложением 

Для запуска api в контейнере выполните последовательность команд:

````
cd stocks_products
docker build -t netology_api_docker .   
docker run -p 8000:8000 --name netology_api_docker  netology_api_docker 
````