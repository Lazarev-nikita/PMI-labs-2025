# PMI-labs-2025
## Репозиторий предназначен для сдачи лабораторных работ 1 курса ПМИ
____
### Для того, чтобы сдать работу, Вам нужно:
1. Зарегистририроваться на GitHub. Предпочтительно использование никнейма, из котого понятно ваше имя.
2. Установить и настроить себе Git, используя инструкции например [отсюда](https://git-scm.com) или [отсюда](https://docs.github.com/ru/get-started/getting-started-with-git/set-up-git).
3. Сделать fork данного репозитория
4. Склонировать его себе на машину при помощи команды:  
``` 
$ git clone https://github.com/Polina-Petrova07/PMI-labs-2025
```
____
### Дальнейшие действия:  
+ После того, как Вы склонируете репозиторий, нужно перейти в директорию (в папку на компьютере со склонированным репозитерием)
```
$ cd PMI-labs-2025
```
+ Создать и переключиться на ветку, в которой Вы будете работать над лабораторной:
```
$ git checkout -b ivanov_labWork_1
```
В названии ветки доложна быть указана Ваша фамилия.  
#### **Важно!** Следите за тем, чтобы Вы работали в **СВОЕЙ** ветке!

Выполнив действия выше, можно приступать к работе)  
#### Файл с отчетом тоже должен находиться в вашей ветке.  
### Когда лабораторная и отчет будут готовы, подготовье и зафиксируйте необходимые файлы, отправьте изменения:
```
$ git add <нужные файлы или ключ -A, если все>
$ git commit -m "<название/описание коммита>"
$ git push origin ivanov_labWork_1
```

### После этого сделайте ```Pull request``` в основной репозиторий (из вашей ветки)
Название pull request должно быть:
```
<Фамилия Имя>. Лабораторная <Номер лабораторной>. <Название задачи>.
Иванов Иван. Лабораторнаяа 1. Поиск значений функций при помощи рядов Тейлора.
```
