# gb_cloud


Взаимодействие клиент-сервер будет осуществляться по сети.
По библиотеке пока не уверен, скорее всего Netty.
Файлы до 10мб будут пересылаться целиком, больше 10мб - частями (скорее всего, сериализованные объекты). 
Служебные команды будут пересылаться с самим файлом, в явном виде.
В базе данных будет храниться информация о клиенте (регистрация, аутентификация по логин/пароль).
Файлы будут храниться на локальной машине сервера.  
Структура каталогов и файлов будет передаваться с файлом.
В целом, по реализации каждого из пунктов с вытекающими, еще нет полного понимания что лучше/хуже.
