# Работа с файловой системой
**pwd** — вывести полный путь до текущей директории;
```bash
$ pwd

/home/username/dir_name
```

**ls** — вывести содержимое текущей директории;
```bash
$ ls

dir_name_1 dir_name_2 file_name.txt
```

**ls** */путь_до_директории/имя_директории* — вывести содержимое указанной директории;
```bash
$ ls /home/username/dir_name_1

dir_name_3 file_name_1.txt
```

**cd** — перейти к корневой директории;
```bash
$ cd
```

**cd** *..* — перейти выше на один уровень от текущей папки;
```bash
$ cd ..
```

**cd** *имя_директории* - перейти в указанную директорию;
```bash
$ cd dir_name
$ cd /home/username/dir_name
```

**mkdir** *имя_директории* - создать директорию в текущей;
```bash
$ mkdir new_dir_name
$ ls

dir_name_1 dir_name_2 file_name.txt new_dir_name
```

**mkdir** */полный_путь_от_корневой_директории/имя_новой_директории/* — создать директорию по указанному пути;
```bash
$ mkdir /home/username/dir_name_1/new_dir_name
$ ls /home/username/dir_name_1

dir_name_3 file_name_1.txt new_dir_name 
```

**touch** *имя_файла* - создать файл в текущей директории;
```bash
$ touch new_file.txt
$ ls 

dir_name_1 dir_name_2 file_name.txt new_dir_name new_file.txt
```

**touch** */полный_путь_от_корневой_директории/имя_файла* — создать файл по указанному пути;
```bash
$ touch /home/username/dir_name_1/new_file.txt
$ ls /home/username/dir_name_1

dir_name_3 file_name_1.txt new_dir_name new_file.txt
```

**cat** *имя_файла* — вывести содержимое файла в терминал;
```bash
$ cat new_file.txt

Hello Linux
```

**mv** *текущее_имя_файла новое_имя_файла* — переименовать файл;
```bash
$ touch new_file.txt old_file.txt
$ ls 

dir_name_1 dir_name_2 file_name.txt new_dir_name old_file.txt
```

**rm** *имя_файла* — удалить файл;
```bash
$ rm old_file.txt
$ ls 

dir_name_1 dir_name_2 file_name.txt new_dir_name
```

**cp** */путь_до_файла/имя_файла /новый_путь_до_файла/имя_файл*а — копировать указанный файл в другую директорию. В пути "куда" копируется файл можно указать ему другое имя.
```bash
$ rm file_name.txt /home/username/dir_name_2/file_name.txt
$ ls /home/username/dir_name_2

file_name.txt
```

**clear** — очистить окно терминала от прошлых выводов;
