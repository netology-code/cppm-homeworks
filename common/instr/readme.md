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
Вы увидите окно с выбором шаблона проекта. 

Для примера мы рассмотрим создание консольного приложения. 
Консольное приложение - это тип программного приложения, которое выполняется в консольном (текстовом) интерфейсе. В консольном приложении взаимодействие с пользователем осуществляется через командную строку или другой текстовый интерфейс, а ввод и вывод информации происходит в текстовом формате.

Выберите «Консольное приложение» и щёлкните по кнопке «Далее»:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/8.PNG)

Вы увидите окно с настройками нового проекта. Укажите его название, расположение на жёстком диске.

Нажмите кнопку «Создать»:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/9.PNG)

### Знакомимся с Visual Studio
После этого Visual Studio создаст новый проект и сразу откроет его вам:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/10.PNG)

Окно Visual Studio состоит из нескольких зон. По центру располагается главная зона, в которой вы пишете код:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/11.PNG)

В главной зоне находятся комментарии к проекту. Их можно удалить, чтобы не мешали работе:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/49.PNG)

Сверху находятся панели управления Visual Studio и проектом, с которым вы работаете: 

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/12.PNG)

Справа находится зона управления файлами и проектами внутри одного решения:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/13.PNG)

В Visual Studio очень много возможностей. Например, можно менять размеры зон. Для этого нужно поместить курсор на границу между зонами, щёлкнуть и потянуть:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/14.PNG)

В зоне справа: 
- "Внешние зависимости" - всё, что мы используем для сборки проекта.
- "Исходные файлы" - файлы, которые мы создаём. Как правило, код на языке C++ состоит из 2-х видов файлов: заголовочный файл и файл непосредственной реализации (.cpp).
- "Файлы ресурсов" - ресурсы проекта, например, для графических приложений это могут быть иконки.
  
![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/50.PNG)


### Собираем проект
В Visual Studio перед тем, как запустить проект, нужно его собрать — скомпилировать. 

Это можно сделать в 2 режимах: Debug и Release.
Debug - режим, который используется для внутреннего тестирования программы. При возникновении ошибок он позволяет программисту подключиться и отладить код. 
Release - режим, который используется при передаче финальной версии программы заказчику.

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/51.PNG)

Также можно выбрать разрядность процессора: x64 или x86, которая зависит от архитектуры процессора. 
Если мы соберём программу на х86, она запустится и будет работать на обоих типах процессоров - как на x86 (32-битных), так и на x64 (64-битных). 
Однако, если мы соберём программу для архитектуры x64 (64-битной), она не запустится на процессоре с архитектурой x86 (32-битной). Программы, скомпилированные для 64-битной архитектуры, требуют наличия 64-битных операционных систем и процессоров для работы.

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/52.PNG)

Для того, чтобы собрать проект щёлкните пункт меню "Сборка" -> "Собрать решение":

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/15.PNG)

При первом запуске IDE собирает полностью все файлы, весь проект. 
Далее, в ходе работы, выбирайте функцию "Собрать решение", чтобы пересобрать только те файлы, в которых было изменение. IDE автоматически их определит.
В случае, если вы выберите "Пересобрать решение", процесс сборки всего проекта начнётся заново. Это, как правило, занимает много времени.

Внизу появится новая зона — «Вывод». В ней вы увидите результаты сборки вашего решения. На самом деле, сборка производится автоматически при запуске проекта, если в ней есть необходимость:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/16.PNG)

### Запускаем проект
Для запуска вашей программы щёлкните по кнопке «Локальный отладчик Windows» или нажмите F5:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/17.PNG)

После запуска с отладкой появится консоль, в которую будет выводить ваша программа:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/18.PNG)

### Отладка
Часто бывает так, что нужно остановить программу в каком-то месте и посмотреть на текущие значения переменных, пошагово выполнить 
программу дальше и проследить, как меняются переменные. Этот процесс называется отладкой.

Отладка позволяет разработчикам эффективно находить и исправлять ошибки в своем коде, улучшая качество программы и сокращая время разработки.

В Visual Studio доступны различные инструменты отладки, такие как точки останова, которые останавливают выполнение программы в определенной точке, чтобы проанализировать ее состояние; окно обозревателя переменных, которое отображает значения переменных во время выполнения; окно вывода, в котором можно просматривать результаты выполнения программы и выводить отладочные сообщения; окно шагов, которое управляет шагами по коду; а также множество других инструментов и функций. 

Для того, чтобы поставить точку останова, щёлкните курсором в области слева от кода — появится красный кружок:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/55.PNG)

Нажмите кнопку «Локальный отладчик Windows» или F5. Когда программа запустится и её выполнение дойдёт до строчки с точкой останова, она остановится и будет ждать действий программиста. 

Вот так выглядит прерванная на точке останова программа. Жёлтая стрелочка указывает, где сейчас находится программа:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/54.PNG)

Можно посмотреть состояние переменных в этот момент программы, а также шагнуть на следующую строчку (F10) или продолжить выполнение программы (F5). Больше инструментов доступно в пункте меню «Отладка»:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/56.PNG)

Также можно запустить программу без отладки:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/53.PNG)

### Расположение в файловой системе

В отличие от REPL, наша программа теперь хранится в виде файлов и директорий на нашем компьютере. Чтобы открыть место расположения файлов, щёлкните правой кнопкой мыши по вашему проекту в правой зоне и в контекстном меню выберите «Открыть папку в проводнике»:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/29.PNG)

Откроется обычный проводник, в котором вы можете увидеть директорию, в которой хранятся файлы вашего проекта:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/30.PNG)

### Пишем новый код
Давайте теперь напишем новый код. Например, поприветствуем пользователя на русском. Добавим строку и запустим отладку:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/19.PNG)

Если появится окошко с сообщением о том, что проект устарел и его нужно пересобрать, поставьте галочку в поле «Больше не выводить это окно» и нажать кнопку «Да». Это нужно делать всегда, чтобы изменения, которые вы внесли в код, повлияли на работу программы.

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/5.PNG)

Вместо нашего текста появились какие-то символы:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/21.PNG)

### Чиним русский язык

Проблема возникла из-за несоответствия кодировок. Чтобы её решить, добавьте в начало функции main такую строчку:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/22.PNG)

Получится вот так:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/23.PNG)

Теперь запустим:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/24.PNG)

Функция setlocal позволяет правильно отображать и обрабатывать данные в соответствии с заданными локальными (региональными) настройками. Локальные настройки определяют язык, форматы дат, времени, чисел, валюты и другие параметры.

### Разбираемся с ошибками

Если в процессе написания кода мы допустим синтаксическую ошибку (а мы допустим), Visual Studio подсветит её для нас. Наведя курсор, можно узнать больше об ошибке:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/25.PNG)

Если мы не заметим подсветку (такое тоже произойдёт), то при попытке запуска перед нами появится окно. Если мы нажмём «Да», то тогда запустится последний успешно собранный вариант вашей программы — без последних изменений. Этого обычно не требуется, поэтому стоит поставить галочку в поле «Больше не выводить это окно» и нажать «Нет»

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/26.PNG)

В нижней зоне у нас появилась новая вкладка «Список ошибок» и сам список ошибок, обнаруженных во время сборки программы:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/27.PNG)

Если переключиться на вкладку «Вывод», мы увидим, что попытка сборки проекта не удалась:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/28.PNG)

### Документация по функциям CPP

![ссылка](https://en.cppreference.com/w/)

- cppreference.com

### Запись текста в файл

Для расширения функционала C++ используются дополнительные библиотеки. Чтобы начать работу с функциями, классами и объектами, предоставляемыми библиотекой, необходимо подключить соответствующий заголовочный файл, описывающий ее функционал.

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/32.1.PNG)

Создайте файл на компьютере:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/34.PNG)

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/35.PNG)

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/36.PNG)

Напишите код для открытия файла 1.txt и проверки, открылся ли он:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/32.2.PNG)

Запустите отладчик, чтобы проверить открылся ли он:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/37.PNG)

Добавьте в файл текст:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/39.PNG)

Запустите отладчик и проверьте, появился ли текст в документе:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/40.PNG)

Чтобы перенести текст на новую строку, используйте операцию:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/41.PNG)

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/42.PNG)

Если вы больше не используете файл, закройте его:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/38.PNG)

### Чтение текст из файла

Подготовьте файл и текст:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/48.PNG)

Добавьте заголовочный файл "string". 

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/45.PNG)

Если вы планируете только считывать информацию из файла, а не записывать в него, испьзуйте класс "ifstream" (input file stream). Часто это помогает уменьшить объём кода, который нужно написать.

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/46.PNG)

Напишите код:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/44.PNG)

Запустите отладчик и убедитесь, что текст из документа считался:

![Image alt](https://github.com/netology-code/cppm-homeworks/blob/main/common/instr/47.PNG)















