## Laboratory work II

Данная лабораторная работа посвещена изучению утилит для разработки проектов

## Tasks

- [x] 1. Ознакомиться со ссылками учебного материала
- [x] 2. Выполнить инструкцию учебного материала
- [x] 3. Составить отчет и отправить ссылку личным сообщением в **Slack**
 
## Tutorial

```bash
//создание переменных
$ export GITHUB_USERNAME=Bozey98
$ export GIST_TOKEN=forlesson
$ alias edit=vim
```

```bash
//устанавливаем gistup
$ npm install -g gistup
```

```bash
//сохраняем token в файл
$ cat > ~/.gistup.json <<EOF
{
  "token": "${GIST_TOKEN}"
}
EOF
```

```bash
//создаем новые директории
$ cd ~
$ mkdir -p workspace/labs/projects/
$ mkdir -p workspace/labs/tasks/
$ mkdir -p workspace/labs/repotrs/
```

## Report

```bash
//переходим в директорию .../labs
$ cd ~/workspace/labs/
//создаем переменную
$ export LAB_NUMBER=02
// клонируем 
$ git clone https://github.com/tp-labs/lab${LAB_NUMBER} tasks/lab${LAB_NUMBER}
//создаем новую директорию
$ mkdir repotrs/lab${LAB_NUMBER}
//копируем файл README.md
$ cp tasks/lab${LAB_NUMBER}/README.md repotrs/lab${LAB_NUMBER}/REPORT.md
//переходим в директорию .../repotrs
$ cd repotrs/lab${LAB_NUMBER}
$ edit REPORT.md
$ gistup -m "lab${LAB_NUMBER}"
```

## Links

### Unix commands

- [ar](https://en.wikipedia.org/wiki/Ar_(Unix)) стандартная утилита Unix, архиватор, не использующий сжатия данных
- [cat](https://en.wikipedia.org/wiki/Cat_(Unix)) утилита UNIX, выводящая последовательно указанные файлы, таким образом, объединяя их в единый поток
- [cd](https://en.wikipedia.org/wiki/Cd_(command)) команда командной строки для изменения текущего рабочего каталога в Unix, DOS и других операционных системах
- [cp](https://en.wikipedia.org/wiki/Cp_(Unix)) команда Unix в составе GNU Coreutils, предназначенная для копирования файлов из одного в другие каталоги
- [cut](https://en.wikipedia.org/wiki/Cut_(Unix)) команда выборки отдельных полей из строк файла
- [echo](https://en.wikipedia.org/wiki/Echo_(command)) команда Unix, предназначенная для отображения строки текста
- [env](https://en.wikipedia.org/wiki/Env_(shell)) UNIX‐утилита, исполняющая команду с изменением окружения
- [ex](https://en.wikipedia.org/wiki/Ex_(editor)) расширение редактора ed, наиболее значительным добавлением к которому является возможность экранного редактирования
- [file](https://en.wikipedia.org/wiki/File_(command)) команда Unix, предназначенная для определения типа файла
- [find](https://en.wikipedia.org/wiki/Find) утилита поиска файлов по имени и другим свойствам, используемая в UNIX‐подобных операционных системах
- [ls](https://en.wikipedia.org/wiki/Ls) утилита Unix, которая печатает в стандартный вывод содержимое каталогов
- [man](https://en.wikipedia.org/wiki/Man_page) команда Unix, предназначенная для форматирования и вывода справочных страниц
- [mkdir](https://en.wikipedia.org/wiki/Mkdir) в операционной системе Unix, Linux, DOS, Windows — команда для создания новых каталогов
- [mv](https://en.wikipedia.org/wiki/Mv) утилита в UNIX и UNIX-подобных системах, используется для перемещения или переименования файлов
- [nm](https://en.wikipedia.org/wiki/Nm_(Unix)) команда в операционной системе UNIX, печатающая информацию о бинарных файлах, прежде всего таблицу имён
- [ps](https://en.wikipedia.org/wiki/Ps_(Unix)) программа в UNIX, Unix-подобных и других POSIX-совместимых операционных системах, выводящая отчёт о работающих процессах
- [pwd](https://en.wikipedia.org/wiki/Pwd) консольная утилита в UNIX-подобных системах, которая выводит полный путь от корневого каталога к текущему рабочему каталогу: в контексте которого (по умолчанию) будут исполняться вводимые команды
- [rm](https://en.wikipedia.org/wiki/Rm_(Unix)) утилита в UNIX и UNIX-подобных системах, используемая для удаления файлов из файловой системы
- [sed](https://en.wikipedia.org/wiki/Sed) потоковый текстовый редактор, применяющий различные предопределённые текстовые преобразования к последовательному потоку текстовых данных
- [touch](https://en.wikipedia.org/wiki/Touch_(Unix)) команда Unix, предназначенная для установки времени последнего изменения файла или доступа в текущее время. Также используется для создания пустых файлов
### Package Managers

- [apt](http://help.ubuntu.ru/wiki/apt) | [dnf](https://en.wikipedia.org/wiki/DNF_(software)) | [yum](https://fedoraproject.org/wiki/Yum/ru)
- [brew](https://brew.sh) | [linuxbrew](http://linuxbrew.sh)
- [npm](https://docs.npmjs.com)

### Software

- [curl](https://www.gitbook.com/book/bagder/everything-curl/details)
- [wget](https://www.gnu.org/software/wget/manual/wget.pdf)
- [clang](https://clang.llvm.org)
- [g++](https://gcc.gnu.org/onlinedocs/gcc-4.0.2/gcc/G_002b_002b-and-GCC.html)
- [make](https://en.wikipedia.org/wiki/Make_(software))
- [open](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man1/open.1.html)
- [openssl](https://www.openssl.org)
- [nano](https://www.nano-editor.org)
- [tree](https://linux.die.net/man/1/tree)
- [vim](http://www.vim.org)

```
Copyright (c) 2017 Братья Вершинины
```
