Написать приложение:
Содержит SOAP-сервис, имеющий:
	Метод Date whatTimeIsItNow() - возвращает текущее время на сервере
	Метод String[] ls(String dir) - возвращает имена файлов/поддиректорий в указанной параметром метода директории (на сервере)
Содержит REST-сервис, имеющий:
	Метод, возвращающий файл по его полному пути
Содержит клиент, вызывающий SOAP.whatTimeIsItNow, SOAP.ls, REST
 
Необходимо распечатывать в консоль, что происходит (что-то послали, что-то приняли, что-то произошло, ...)
В качестве средства реализации можно брать как встроенные средства Java, так и библиотеки Web-Service'ов
Корректно обрабатывать, если сервер ещё не поднялся, а клиент уже к нему обращается
 
Реализовать сборку проекта и дистрибутива на Apache Maven
