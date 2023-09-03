# Library

## Оглавление

1. [Введение](#Введение)
2. [Структура](#Структура)
3. [Добаление книги](#Добаление-книги)
   1. [Порядок добавления](#Порядок-добавления)
   2. [Оформление файлов](#Оформление-файлов)
   3. [Требования к структуре](#Требования-к-структуре)
4. [Отзывы и пожелания](#Отзывы-и-пожелания)

## Введение
[Оглавление](#Оглавление)
___

Проект "Библиотека" задумывался как открытая хранилище конспектов и проработки литературы (преимущественно технической)
в целях самообразования. Проработка книг с ведением картотеки, которая в будущем может служить справочникогм по тому или
иному вопросу, считается самым эффективным способом чтения книг для самообразования, однако оно также является очень
затратным по времени. "Библиотека" является попыткой сэкономить самый важный ресурс человечества за счёт разделения труда
по изучению литературы между участниками проекта (насколько это разделение в принципе возможно без вреда самообразованию).


## Структура
[Оглавление](#Оглавление)
___

Масштабируемой единицей проекта является книга, брошура или иная литература (далее книга). Книги хранятся в двухуровневой
файловой системе. Директория верхнего уровня имеет название общирной области знаний либо вопроса
(развитие, создание компьютерных игр, бекэнд разработка и т. д.). Директории нижнего уровня содержат книги, посвящённые
изучению более конкретной темы (методики чтения, геймдизайн, базы данных...).

Директория книги имеет название, соответствующее следующему шаблону: `<Ф. И. Отчество автора> - <Название книги>`.
По возможности директория должна содержать экземпляр книги (желательно в .pdf). Директория книги содержит текстовый файл,
в котором приведены цель, с которой читатель, добавивший книгу, брался за её изучение, и выводы, сделанные читателем
после прочтения. Основное содержание директории книги представляют файлы с конспектами, заметками и иными материалами,
составленными по книге.

## Добаление книги
[Оглавление](#Оглавление)
___

Библиотека задумывалась как открытая площадка, поэтому любой участник имеет возможность добавлять директории своих книг,
которые он собирается проработать. 

### Порядок добавления
[Оглавление](#Оглавление)
___

Для добавления своей книги, пользователю сначала следует сделать fork проекта на свой Github аккаунт (исключение состовляют
владелец и модераторы, имеющие доступ к редактированию файлов).

Для каждой книги создаётся issue:

- название issue соответствует названию будущей директории книги;
- В Assignees следует указать собственный Github аккаунт;
- В Labels должна присутствовать метка `new book`;
- Первый комментарий под issue должен содержать путь в файловой системе, где планируется разместить книгу.

Работа над книгой ведётся в отдельной git ветке. Название ветки также соответствует названию директории книги
(вместо пробелов `_`). Ведение ветки остаётся на усмотрение пользователя, жёстких требований нет.

>Совет. Удобным правилом нейминга коммитов в ветке может быть указание на место в книге, до которого продвинулась проработка.

Ветка завершается окончанием работ над книгой и дописыванием вывода к книге в соответствующем файле. Для добавления
новых книг на проект, следует создать pull request, который будет обработан владельцем либо модератором, он же закроет
соответсвующие запросу issues.

### Оформление файлов
[Оглавление](#Оглавление)
___

### Требования к структуре
[Оглавление](#Оглавление)
___

## Отзывы и пожелания
[Оглавление](#Оглавление)
___

