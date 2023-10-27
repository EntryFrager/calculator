# :muscle: Процессор :muscle:

Данный проект содержит в себе сразу три программы: ```ассемблер```, ```дизассемблер``` и ```процессор```. Ассемблер переводит пользовательский код в машинный и записывает его в бинарный файл. Дизассемблер работает, соответственно в обратную сторону. Процессор же, считывает код из бинарного файла и выполняет переданные ему инструкции, а после выводит результат в файл ```"result.txt"```. В документации вы можете ознакомиться со спиком комманд, которые может выполнять данный процессор.

## Установка программы

### 1.При помощи этой команды(её нужно вводить в командной строке) скачай все файлы в один свой файл.

    git clone https://github.com/EntryFrager/calculator.git

### 2. Далее в командной строке открой один из файлов (ассемблер, дизассеблер или процессор), и напиши:

    make

### 3. Все, программа готова к использованию, для этого в командной строке пропиши:

    assembler.exe / disassembler.exe / calc.exe

### 4. Для удаления объектных файлов, созданных на шаге 2, пропиши в командной строке:

    make clean

***

#### В ассемблере также выполняется вывод в текстовый файл общей информации о твоих коммандах, для их проверки.

	+------------+------------+------------+------------+------------+------------+
	|  NAME_CMD  |  CODE_CMD  |  HEX_SPEAK |  VALUE_ARG |  VALUE_REG |  VALUE_RAM |
	+------------+------------+------------+------------+------------+------------+
	|          in|          20|          14|           0|           0|           0|
	+------------+------------+------------+------------+------------+------------+
	|          in|          20|          14|           0|           0|           0|
	+------------+------------+------------+------------+------------+------------+
	|          in|          20|          14|           0|           0|           0|
	+------------+------------+------------+------------+------------+------------+
	|         pop|          67|          43|           0|           3|           0|
	+------------+------------+------------+------------+------------+------------+
	|         pop|          67|          43|           0|           2|           0|
	+------------+------------+------------+------------+------------+------------+
	|         pop|          67|          43|           0|           1|           0|
	+------------+------------+------------+------------+------------+------------+
	|        call|          36|          24|          10|           0|           0|
	+------------+------------+------------+------------+------------+------------+
	|        push|          66|          42|           0|           1|           0|
	+------------+------------+------------+------------+------------+------------+
	|         out|           1|           1|           0|           0|           0|
	+------------+------------+------------+------------+------------+------------+