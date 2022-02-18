## Лабораторная работа 1. Диаграмма Ганта

### Создайте диаграмму Ганта для проекта по разработке корпоративного сайта для какой-то компании или организации (например, для РГПУ им. А. И. Герцена). Экспортируйте её как картинку (jpeg, jpg или png) и разместите в репозитории. 

### Для каждой задачи, которую вы расположите на диаграмме, проанализируйте потенциальные риски и выпишите их в отдельном файле risks.md, который также расположите в репозитории. ### Для каждого риска оцените вероятность возникновения риска и опишите кратко какие действия возможно выполнить, чтобы риска избежать или устранить последствия его реального возникновения.

### Диаграмма Ганта может быть создана с помощью одного из сервисов: 
### 1. Realtimeboard (https://realtimeboard.com/ru/).
### 2. draw.io (https://www.draw.io, раздел "Flowcharts").
### 3. Teamweek (https://teamweek.com).

## Для создания можно использовать и другой сервис, если в нём есть функция экспорта в изображение.

![Лабораторная работа 1  Диаграмма Ганта](https://github.com/RainyBaam/UPP/blob/main/download.png)

# Лабораторная 5. Макетирование

# Лабораторная 6. UML-диаграмма
## Описание предметной области
В Герценовском университете проводится конференция. Планируется постерная сессия (в зале выставляются плакаты и меж них ходят авторы постеров, с которыми можно пообщаться), сессия докладов (2 потока) и публикация сборника.
Требуется создать информационную систему, которая бы позволяла автоматизировать решение задач, которые должны выполнить организаторы этой конференции. 
## Основные функции:
регистрация участников конференции;
нотификация об важных сроках, этапах конференции;
выбор места вывешивания постера;
выбор дня и потока выступления;
загрузка презентации.
##Требования к заданию:
создайте диаграмму прецедентов;
создайте диаграмму (или диаграммы) последовательности (минимум, для 2 функций системы).


# Лабораторная 7. Знакомство с GIT.
## 1) git add
### Команда git add добавляет содержимое рабочей директории в индекс (staging area) для последующего коммита.
## 2) git status
### Команда git status показывает состояния файлов в рабочей директории и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе.
## 3) git diff
### Команда git diff используется для вычисления разницы между любыми двумя Git деревьями.
## 4) git difftool
### Команда git difftool просто запускает внешнюю утилиту сравнения для показа различий в двух деревьях, на случай если вы хотите использовать что-либо отличное от встроенного просмотрщика git diff.
## 5) git commit
### Команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет их слепок во внутренней базе данных, а затем сдвигает указатель текущей ветки на этот слепок.
## 6) git reset
### Команда git reset используется в основном для отмены изменений. Она изменяет указатель HEAD и, опционально, состояние индекса.
## 7) git rm
### Команда git rm используется в Git для удаления файлов из индекса и рабочей директории.
## 8) git mv
### Команда git mv перемещает файл, а затем выполняет git add для нового файла и git rm для старого.
## 9) git clean
### Команда git clean используется для удаления мусора из рабочей директории. Это могут быть результаты сборки проекта или файлы конфликтов слияний.
## 10) git branch
### Команда git branch — это своего рода “менеджер веток”. Она умеет перечислять ваши ветки, создавать новые, удалять и переименовывать их.
## 11) git checkout
### Команда git checkout используется для переключения веток и выгрузки их содержимого в рабочую директорию.
## 12) git pull
### Команда git pull работает как комбинация команд git fetch и git merge, т.е. Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой.
## 13) git archive
### Команда git archive используется для упаковки в архив указанных коммитов или всего репозитория.
## 14) git show
### Команда git show отображает объект в простом и человекопонятном виде. Обычно она используется для просмотра информации о метке или коммите.
## 15) git bisect
### Команда git bisect — это утилита для поиска коммита в котором впервые проявился баг или проблема с помощью автоматического бинарного поиска.
