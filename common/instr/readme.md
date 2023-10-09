# IDE

В этой инструкции:
- Разберёмся, что такое IDE и какие они бывают
- Познакомимся с процессом установки Microsoft Visual Studio 2022 Community Edition
- Узнаем, как работать с MS Visual Studio 2022 CE

## 1. IDE (от англ. Integrated development environment — Интегрированная среда разработки)
Это программы для разработки других программ. Обычно они включают в себя все необходимые инструменты, которые требуются для того, чтобы написать исходный код программы и собрать его в исполняемые файлы.

### Чем IDE отличается от текстового редактора
Текстовый редактор может поддерживать синтаксис разных языков программирования, но в основном не предоставляет дополнительные инструменты и функции

IDE объединяет в себе текстовый редактор, компилятор (или интерпретатор) и другие инструменты разработки, предназначенные для упрощения процесса создания программ: автодополнение кода, отладчик, анализ кода, система контроля версий и т.д.

### Какие бывают IDE
- Могут работать только с одним языком программирования
- Могут работать с несколькими языками
- Только платные
- Бесплатные
- Платные и бесплатные версии, которые различаются по условиям использования и функциям

### IDE для C++
1. Microsoft Visual Studio 
2. CLion - IDE от JetBrains
3. Eclipse - с открытым исходным кодом
4. NetBeans - с открытым исходным кодом
5. Xсode - доступна только для macOS

## 2. Установка Microsoft Visual Studio на Windows 10

Далее мы рассмотрим процесс установки Microsoft Visual Studio 2022 Community Edition на компьютер под управлением операционной системы Microsoft Windows 10. У Visual Studio также есть версия для операционной системы macOS. Для беспроблемной установки на вашем компьютере должно быть не менее 15 Гб свободного места, а версия Windows 10 не ниже 1607.

### Шаг 1. Загрузка установщика
Зайдите на страницу загрузки Visual Studio. Для этого перейдите по ссылке или наберите в поисковике «Microsoft Visual Studio Community». Вы попадёте на такую страницу:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/1.PNG)

### Шаг 2. Запуск установщика
Щёлкните по кнопке «Скачать» — начнётся скачивание установщика (VisualStudioSetup.exe). После загрузки запустите установщик. 
Нажмите «Продолжить»

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/2.PNG)

### Шаг 3. Выбор рабочих нагрузок
Мы увидим окно выбора рабочих нагрузок для установки. Нужно сдвинуть ползунок вниз и выбрать пункт «Разработка классических приложений на C++»:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/3.PNG)

### Шаг 4. Выбор места на диске
Во вкладке «Расположение установки» можно выбрать раздел на жёстком диске с достаточным объёмом памяти для установки программы

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/4.PNG)

### Шаг 5. Процесс установки
После выбора щёлкните по кнопке «Установить» в нижнем правом углу. У вас появится вот такое окно:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/5.PNG)

### Шаг 6. Перезагрузка
После окончания установки компьютер попросит перезагрузку. Перезагрузите компьютер

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/6.PNG)

## 3. Знакомство с Visual Studio 2022

### Запуск Visual Studio
После перезагрузки нам нужно запустить Visual Studio. Для этого можете просто открыть меню «Пуск» и ввести в строке поиска слово «visual». Щёлкните по Visual Studio 2022. 
Программа предлагает следующие возможности:
- Клонирование репозитория - работать с проектом, который выложен на Git хостинге
- Открыть проект - открыть готовый проект, созданный в Visual Studio, на локальном компьютере
- Открыть локальную папку - открыть папку с проектом на компьютере
- Создание проекта - создание нового проекта

Нажмите на кнопку «Создание проекта»:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/7.PNG)

### Создание проекта C++
Вы увидите окно с выбором шаблона проекта. Выберите «Консольное приложение» и щёлкните по кнопке «Далее»:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/8.PNG)

Вы увидите окно с настройками нового проекта: его название, расположение и пару других настроек. Оставьте всё как есть и нажмите кнопку «Создать»:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/9.PNG)

### Знакомимся с Visual Studio
После этого Visual Studio создаст новый проект и сразу откроет его вам:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/10.PNG)

Окно Visual Studio состоит из нескольких зон. По центру располагается главная зона, в которой вы пишете код:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/11.PNG)

Сверху находятся панели управления Visual Studio и проектом, с которым вы работаете: 

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/12.PNG)

Справа находится зона управления файлами и проектами внутри одного решения (подробнее рассмотрим на следующих лекциях):

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/13.PNG)

В Visual Studio очень много возможностей. Например, можно менять размеры зон. Для этого нужно поместить курсор на границу между зонами, щёлкнуть и потянуть:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/14.PNG)

### Собираем проект
В отличие от REPL, в Visual Studio перед тем, как запустить проект, нужно его собрать — скомпилировать. Для этого щёлкните пункт меню «Сборка -> Собрать решение»:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/15.PNG)

Внизу появится новая зона — «Вывод». В ней вы увидите результаты сборки вашего решения. На самом деле, сборка производится автоматически при запуске проекта, если в ней есть необходимость:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/16.PNG)

### Запускаем проект
Для запуска вашей программы щёлкните по кнопке «Локальный отладчик Windows» или нажмите F5:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/17.PNG)

После запуска появится консоль, в которую будет выводить ваша программа:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/18.PNG)

### Пишем новый код
Давайте теперь напишем новый код. Например, поприветствуем пользователя на русском. Добавим строку и запустим отладку:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/19.PNG)

Если появится окошко с сообщением о том, что проект устарел и его нужно пересобрать, поставьте галочку в поле «Больше не выводить это окно» и нажать кнопку «Да». Это нужно делать всегда, чтобы изменения, которые вы внесли в код, повлияли на работу программы.

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/5.PNG)

Вместо нашего текста появились какие-то символы. Что произошло и что делать, как вы думаете?

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/21.PNG)

### Чиним русский язык

Проблема возникла из-за несоответствия кодировок. Чтобы её решить, добавьте в начало функции main такую строчку:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/22.PNG)

Получится вот так:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/23.PNG)

Теперь запустим:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/24.PNG)

### Разбираемся с ошибками

Если в процессе написания кода мы допустим синтаксическую ошибку (а мы допустим), Visual Studio подсветит её для нас. Наведя курсор, можно узнать больше об ошибке:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/25.PNG)

Если мы не заметим подсветку (такое тоже произойдёт), то при попытке запуска перед нами появится окно. Если мы нажмём «Да», то тогда запустится последний успешно собранный вариант вашей программы — без последних изменений. Этого обычно не требуется, поэтому стоит поставить галочку в поле «Больше не выводить это окно» и нажать «Нет»

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/26.PNG)

В нижней зоне у нас появилась новая вкладка «Список ошибок» и сам список ошибок, обнаруженных во время сборки программы:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/27.PNG)

Если переключиться на вкладку «Вывод», мы увидим, что попытка сборки проекта не удалась:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/28.PNG)

### Расположение в файловой системе

В отличие от REPL, наша программа теперь хранится в виде файлов и директорий на нашем компьютере. Чтобы открыть место расположения файлов, щёлкните правой кнопкой мыши по вашему проекту в правой зоне и в контекстном меню выберите «Открыть папку в проводнике»:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/29.PNG)

Откроется обычный проводник, в котором вы можете увидеть директорию, в которой хранятся файлы вашего проекта:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/30.PNG)

### Работа с файлами

Для расширения функционала C++ используются дополнительные библиотеки. Чтобы начать работу с функциями, классами и объектами, предоставляемыми библиотекой, необходимо подключить соответствующий заголовочный файл, описывающий ее функционал.

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/32.1.PNG)

Затем написать программу:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/32.2.PNG)






