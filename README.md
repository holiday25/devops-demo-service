### Как запустить сервис?
Для того чтобы запустить сервис сначала склонируйте репозитории используя команду ```git clone```

##### Затем перейди в этот репозитории используя команду: 

``` docker compose up ```  

вы сможете запустить сервис

#### Если вы до этого запускали похожий проект, то используйте команду 

``` docker system prune --all ```

для очистки системы docker. Эта команда удалить все "контейнеры,  образы  и т.д" так что будьте внимательны перед выполнением


#### Затем опять запустите команду

``` docker compose up ```

Сервис будет доступен по адресу "localhost:8000/admin"
 
#### Для сборки свежего образа используйте команду:

``` docker compose up --build ```
 
Запуск тестирования будет запускать на каждый push в ветку main результаты тестов можно увидеть в разделе Actions
