# Github-Analysis

Пакет dataLoader - jar файл для загрузки данных через gitHub api

img-hdp-zeppelin - дистрибутив zeppelin :
  1) docker build -t img-hdp-zeppelin .
  2) docker run -it --name zeppelin -p 50090:50090 -p 50075:50075 -p 50070:50070 -p 8042:8042 -p 8088:8088 -p 4040:4040 -p 4044:4044 -p 8888:8888 --hostname localhost        img-hdp-zeppelin.

Пакет results - результаты в виде zeppelin отчета (открывается через zeppelin)
