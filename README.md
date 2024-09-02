# -0-Python-Installation-and-configuration

## Установка и настройка Python

**Python** — это высокоуровневый язык программирования, который используется для разработки веб-приложений, автоматизации задач, анализа данных, машинного обучения и многого другого. Он известен своей простой и понятной синтаксической структурой, что делает его идеальным как для начинающих программистов, так и для профессионалов.

## 1. Где скачать Python
Python можно скачать с официального сайта: [python.org](https://www.python.org/downloads/). На этом сайте всегда доступны последние стабильные версии языка для различных операционных систем:

- **Windows**
- **macOS**
- **Linux**
  
А также документация, примеры и помощь по работе с языком программирования.

## 2. Как установить
**В примере показано, как установить Python на OS Windows x64** <br>
1. Зайдите на официальный сайт Python. <br>
   s1
 
2. Перейди на страницу загрузок и выбери подходящую версию для твоей операционной системы. Вы можете увидеть множество версий Python, такие как: 3.10, 3.11, 3.12 и последующие включают множество улучшений и новых возможностей. Скачайте установочный файл и запусти его.<br>
   s2
   
3. Во время установки убедись, что выбрана опция "Add Python to PATH", чтобы в дальнейшем можно было использовать Python из командной строки.  <br>
   s3

4. Дождитесь конца установки и закройте окно. <br>
   s4

Если всё проло успешно, то теперь у вас есть интерпретатор Python (Интерпретатор — это программа, которая выполняет команды, написанные на каком-то языке программирования.) и IDLE — это интегрированная среда разработки и обучения на языке Python.) <br>
   s5

   
## 3. О IDLE
   
IDLE (Integrated Development and Learning Environment) — это простая среда разработки, которая поставляется вместе с Python. Она предназначена для написания, выполнения и отладки кода. IDLE включает в себя редактор кода с подсветкой синтаксиса и консоль Python для быстрого тестирования скриптов.

**Основные функции IDLE:**
- Подсветка синтаксиса.
- Автодополнение кода.
- Простой отладчик для проверки и отладки кода.
- Удобная консоль Python для выполнения команд в режиме реального времени.
- IDLE отлично подходит для начинающих, так как позволяет легко и быстро начать работать с Python без необходимости устанавливать сторонние IDE (например, PyCharm или Visual Studio Code, о них поговорим позже).

## 4. Запуск IDLE

*Запустите IDLE**:
   - На Windows: найдите "IDLE" в меню «Пуск» или просто введите «IDLE» в строке поиска.
   - На macOS: откройте Finder, перейдите в папку «Программы», найдите папку Python и запустите IDLE.
   - На Linux: запустите терминал и введите `idle3`, если он установлен.

2. **Откроется окно консоли Python Shell**:
   - В этом окне можно выполнять команды Python в интерактивном режиме.

4. **Создание нового файла**:
   - Чтобы начать писать код, выберите **File > New File** или нажмите `Ctrl + N` (Windows/Linux) или `Cmd + N` (macOS).
   
5. **Напишите свой код и запустите его**:
   - После написания кода выберите **Run > Run Module** или нажмите `F5`, чтобы выполнить программу.
   - Сохранения обязательны.
   
6. **Использование редактора кода**:
   - IDLE поддерживает подсветку синтаксиса, автодополнение и простую отладку, что делает его удобным для быстрого тестирования и разработки.

**Весь процесс IDLE**

s6

## IDE
## 1. Что такое IDE?

**IDE (Integrated Development Environment)** — это интегрированная среда разработки, предназначенная для создания программного обеспечения. IDE предоставляет разработчику все необходимые инструменты для написания, тестирования, отладки и управления кодом в одном месте. Основные компоненты IDE включают:

- **Редактор кода** с подсветкой синтаксиса и автодополнением.
- **Отладчик** для пошагового выполнения кода и поиска ошибок.
- **Инструменты сборки** для компиляции и запуска программ.
- **Интеграция с системой контроля версий** (например, Git) для управления изменениями в коде.
- **Терминал** для запуска команд напрямую из среды.

## 2. Разница между IDE и IDLE

| Функция                | IDE                            | IDLE                         |
|------------------------|--------------------------------|------------------------------|
| **Комплексность**      | Полнофункциональная среда с расширяемыми возможностями. | Простая среда, минимальные функции. |
| **Редактор кода**      | Поддержка подсветки синтаксиса, автодополнения, рефакторинга и много другого. | Базовый редактор с подсветкой синтаксиса и автодополнением. |
| **Отладка**            | Мощные встроенные отладчики с поддержкой точек останова, просмотра переменных и т. д. | Простой отладчик с ограниченными возможностями. |
| **Поддержка проектов** | Управление большими проектами, интеграция с системами контроля версий, такими как Git. | Не поддерживает управление проектами. |
| **Расширяемость**      | Поддержка плагинов и настроек, позволяющих добавлять новые функции. | Минимальные возможности для кастомизации. |
| **Использование**      | Подходит для крупных проектов и профессиональной разработки. | Подходит для небольших скриптов и обучения. |

## 3. Популярные IDE для Python

### 1. **PyCharm**
   - **Описание**: Одна из самых популярных IDE для Python, разработанная JetBrains. Поддерживает множество функций, таких как отладка, рефакторинг кода, автодополнение и интеграция с Git.
   - **Плюсы**: Мощный отладчик, поддержка тестирования, умный редактор кода, плагины.
   - **Минусы**: Может быть ресурсоемким, особенно на больших проектах.

### 2. **Visual Studio Code (VS Code)**
   - **Описание**: Легкая, но мощная редакторская среда от Microsoft, поддерживающая множество языков, включая Python, через плагины.
   - **Плюсы**: Быстрый, кастомизируемый, поддержка множества расширений, интеграция с Git.
   - **Минусы**: Требует установки плагинов для полной функциональности.

### 3. **Spyder**
   - **Описание**: IDE, ориентированная на научные вычисления и анализ данных. Идеально подходит для работы с библиотеками NumPy, SciPy, Pandas.
   - **Плюсы**: Встроенная поддержка научных пакетов, удобные инструменты для отладки и анализа данных.
   - **Минусы**: Не так много функций для веб-разработки.

### 4. **Jupyter Notebook**
   - **Описание**: Среда, популярная среди специалистов по данным и машинному обучению, поддерживает интерактивное выполнение кода.
   - **Плюсы**: Возможность интерактивного выполнения кода, поддержка визуализации данных.
   - **Минусы**: Ограниченные возможности отладки и работы с большими проектами.

### 5. **Eclipse + PyDev**
   - **Описание**: Eclipse с плагином PyDev предоставляет возможности для Python-разработки, включая отладку, автодополнение и управление проектами.
   - **Плюсы**: Хорошая интеграция с другими языками и системами.
   - **Минусы**: Требует настройки и может быть сложнее в использовании.

Каждая из этих IDE имеет свои особенности и может подойти для различных задач в зависимости от требований и предпочтений.

## 4. Скачать Pycharm

Разберём процесс установки IDE на примере Pycharm. Скачать её можно с [офицального сайта](https://www.jetbrains.com/ru-ru/pycharm/) <br>
На главной странице нажмите "Скачать". <br>
**Важно!** Pycharm бесплатная не для всех языков программирования, поэтому необходимо скачать не "PyCharm Professional", а "PyCharm Community Edition". Она расположена немного ниже. <br>

s7, s8

## 5. Установка PyCharm

1. **После того, как файл скачался, запустите его.**
   Дождитесь, пока установочный файл подготовится к запуску. <br>
   s9 
  

2. **Выберите, куда установить PyCharm.**  
   Рекомендуется оставить путь по умолчанию, но при желании можно выбрать другую папку. <br>
   s10 

3. **Проставьте все галочки на установке компонентов.**  
    
   Выберите параметры, чтобы:
   - Создать ярлык на рабочем столе.
   - Ассоциировать файлы `.py` с PyCharm.
   - Добавить PyCharm в системный PATH для использования в командной строке. <br>
   s11 

4. **Завершите установку.**  
   Нажмите "Install" и дождитесь окончания процесса. После установки можно перезагрузите ПК "Reboot now" и запустить PyCharm. <br>
   s12  


## Настройка Pycharm

