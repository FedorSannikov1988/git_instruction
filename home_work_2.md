![start_rocket](start_rocket.jpg)

## Запрос установленной версии\проверка работоспособности Git

Проверка установленной на ПК версии\проверка работоспособности Git осуществляется с помощью команды:

**git version** или **git --version**

![magic](magic.jpg)

![magic_wand](magic_wand.jpg)

## Регистрация в Git после установки

Регистрация прозводится с помощью двух комманд:

1. **git config --global user.name** где **user.name** ваше имя;

2. **git config --global user.email** где **global user.email** ваша электронная почта;
 
***<u>Можно ввести любые данные Git их не проверяет.</u>***

***<u>Без выполнения данного шага дальнейшие шаги будут невозможны !</u>***

![magic](magic.jpg)

![magic_wand](magic_wand.jpg)

## Инициализация в Git

Инициализация локального репозитория в папке производтся коммандой:

**git init**

После иниуиализации в папке с проектом должна появиться скрытая папка  **.git**

Пример: ![primer_1](primer_1.jpg)

![magic](magic.jpg)

![magic_wand](magic_wand.jpg)

## Получить информацию в Git о его текущем состоянии

Для проверки/получения информации о текущем состоянии необходимо использовать команду **git status**

Данная команда "показывает" изминения между сохраненной версией файла (ctrl + s) и версией полученной с помощью команты **git commit -m " "**.

![magic](magic.jpg)

![magic_wand](magic_wand.jpg)

## Добавление файла или файлов в Git к последующему коммиту/commit

Добавить файла или файлов к следующему коммиту осуществляется с помощью комманды **git add**.

Есть два варианта исполнения данной комманды:

1. **git add <u><имя добавляемого файла></u>** - добавляет только файл имя которого указано

2. **git add .** - добавляет все файлы в папке кроме "закомментированных"/добавленных в файл .gitignore

![magic](magic.jpg)

![magic_wand](magic_wand.jpg)

## Создание коммита/commit в Git добавленных файлов

Создание коммита/commit осуществляется с помощью комманды **git commit -m “message”** где message комментарии к коммиту/commit по которому можно понять что в нем.

![magic](magic.jpg)

![magic_wand](magic_wand.jpg)

## Вывод различных версий проекта в Git

Вывод на экран истории всех коммитов/commit с хеш-кодами осуществляется с помощью двух следующих комманд:

1. **git log** - вывод сухого лога

2. **git log --graph** - вывод ветвей проекта с обозначением когда какая объединялась

![magic](magic.jpg)

![magic_wand](magic_wand.jpg)

## Переход между коммита/commit и/или ветками проекта в Git

Переход между коммита/commit и/или ветками проекта с помощью комманд:

**git checkout <id коммита/commit и/или ветки проекта>**

Переход в **<u>актуальную/основную</u>** ветку проекта осуществляется коммандой **git checkout master**

![magic](magic.jpg)

![magic_wand](magic_wand.jpg)

## Сравнение различных версий файлов проекта в Git

Сравнение с последним коммита/commit (в ветке где сейчас происходят работы) осущевляется по средством комманды **git diff**

![magic](magic.jpg)

![magic_wand](magic_wand.jpg)

## Работа с ветками проектов в Git

* Посмотреть список веток в репозитории проекта **git branch**

* Создать новую ветку в репозитории проекта **git branch <название ветки>**

* Удалить ветку в репозитории проекта **git branch -d <название ветки>**

![explosion_rocket](explosion_rocket.jpg)

![end](end.jpg)