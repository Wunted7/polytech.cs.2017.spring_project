# Key Access
Эта программа позволяет регистрировать и авторизовывать пользователей. Программа считывает время удержания клавиш при печати предоставленного текста. В случае успеха авторизации выводит имя человека. Так же позволяет зарегистрировать нового пользователя.

## Как начать
Эти инструкции помогут вам запустить программу.
Чтобы начать:
````
./key_access
````
### Интрефейс
Авторизация:
![Image alt](http://cdn1.savepice.ru/uploads/2017/5/26/d4b7964b6d9c5e75ddcd62fdb65aef0c-full.jpg)
Для авторизации нужно ввести в консоли 2 и в появившемся окне окне ввести предложенную фразу.

Регистрация:
![Image alt](http://cdn1.savepice.ru/uploads/2017/5/26/5b5972a3d3de3f15b7f39ef9e7966a69-full.jpg)
Для регистрации нужно ввести 1, затем ввести свое имя на английском, затем в появившемся окне окне ввести предложенную фразу несколько раз.

### Структура
Исходный код устроен следующим образом:

Subdirectory | Description
-------------|-------------------
src/         | source files
src/tests     | unit tests
doc/         | documentation

### Сборка
Для сборки программы:
````
make
````
Для удаления программы:
````
make clean
````
Для сборки тестов:
````
make D_UNITY=../Unity check
````
Для сборки документации:
````
make doxygen
````
Для сборки документации в формате PDF:
````
make pdf
````
Для сборки документации в формате HTML:
````
make html
````

## Authors
* **Nikita Ilchenko**  - wunted7@gmail.com
* **Yury Batov**  - batov1998@list.ru

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
