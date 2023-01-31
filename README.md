# Урок 22 - ВЫПОЛНЕННЫЕ НА ТРЕНАЖЁРЕ ЗАДАНИЯ К УРОКУ 22. Шумихин А. 31.01.23
Для начала работы скопируйте репозиторий на локальную машину:
c помощью команды в терминале

`https://github.com/skypro-008/lesson22-and-tests.git`

Откройте склонированный репозиторий в PyCharm.

### Cоздайте виртуальное окружение:

#### Простой вариант:
Pycharm может предложить вам сделать это после того, как вы откроете папку с проектом.
В этом случае после открытия папки с проектом в PyCharm
Появляется всплывающее окно, Creating virtuan envrironment c тремя полями.
В первом поле выбираем размещение папки с вирутальным окружением, как правило это папка venv
в корне проекта
Во втором поле выбираем устанавливаемый интерпритатор по умолчанию (можно оставить без изменений)
Установка зависимостей в данном уроке не требуется

#### Если этого не произошло, тогда следует выполнить следующие действия вручную:
#### Установка виртуального окружения:
1. Во вкладке File выберите пункт Settings
2. В открывшемся окне, с левой стороны найдите вкладку с именем
вашего репозитория (Project: lesson22-and-tests)
3. В выбранной вкладке откройте настройку Python Interpreter
4. В открывшейся настройке кликните на значек ⚙ (шестеренки) 
расположенный сверху справа и выберите опцию Add
5. В открывшемся окне слева выберите Virtualenv Environment, 
а справа выберите New Environment и нажмите ОК

#### Установка зависимостей:
Для данного урока установки зависимостей не требуется.
Задачи можно решить полностью, воспользовавшись встроенными библиотеками Python

### Порядок выполнения заданий
#### Часть 1:

- part1/abstract_class                (тесты+ревью)
- part1/bad_smell_big_class           (тесты+ревью)
- part1/bad_smell_call_chain          (проверяется только на ревью)
- part1/bad_smell_comments            (тесты+ревью)
- part1/bad_smell_dead_code           (тесты+ревью)
- part1/bad_smell_doubles             (тесты+ревью)
- part1/bad_smell_envious_func        (тесты+ревью)
- part1/bad_smell_laizy_class         (тесты+ревью)
- part1/bad_smell_long_method         (проверяется только на ревью)
- part1/bad_smell_long_parameter_list (проверяется только на ревью)



Задачи описаны в комментариях в файле main.py
В текущих заданиях вы будете учиться применять рефакторинг кода
Данный урок имеет свои особенности, и будет проверяться наставниками. 
Однако чтобы помочь Вам подготовить Ваш код к ревью
практически во всех заданиях имеются автотесты, воспользуйтесь ими прежде чем
отправлять свою работу на проверку.

*Обращаем ваше внимание, что для каждого задания предусмотрены свои тесты
и запускать нужно именно те тесты, которые находятся в папке с заданием*
Пожалуйста, запускайте тесты с помощью файла tests_runner.py.