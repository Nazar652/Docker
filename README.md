npm init
Створення node.js app

docker build -t tymchyshyn/dev:1.0 .   
Створення image докера

docker run -p 80:80 -m 100m --cpus="1" sha256:15424ae0877925eb073daa911123e8bb4af956f135e6a12355e6d06b220ab934  
Запуск контейнера з портом 80, обмеженням використання пам'яті 100 МБ та виділеним 1 ядром процесора
