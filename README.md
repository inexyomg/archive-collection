# Итоговая работа по курсу "Цифровая архивация современности. Веб-архивы, большие данные и их применение в исследовательской работе", 2024

Этот репозиторий содержит описание коллекции веб-архивов, созданной с использованием инструмента `wpull` для загрузки данных. Метаданные архивов проанализированы с помощью библиотеки `metawarc`. Кроме того, проведена оценка архивируемости коллекции сайтов на основе ресурса `ArchiveReady`, используя метрику `CLEAR`.

## Краткое описание коллекции

| Сайт               | Объем архива | Время скачивания |
|--------------------|--------------|------------------|
| **sfy-conf.ru**    | XX Мб        | XX мин           |
| **nica.jinr.ru**   | XX Мб        | XX мин           |
| **discuss-science.ru** | XX Мб     | XX мин           |
| **jinr.ru**        | XX Гб        | XX часов XX мин  |
| **lbl.gov**        | XX Гб        | XX часов XX мин  |
| **ihep.su**        | XX Мб        | XX мин           |
| **home.cern**      | XX Гб        | XX часов XX мин  |

Ссылка на архив: [Примерная ссылка на диск или репозиторий]

В рамках этой работы я сформировал архивную коллекцию сайтов, связанных с научными конференциями, физикой высоких энергий и крупными научными проектами в области физики и инженерии. Эти сайты объединяет их академический и исследовательский фокус.

## Описание коллекции

Коллекция включает следующие ресурсы:

1. **sfy-conf.ru** — сайт, посвященный мероприятиям и конференциям, связанным с молодежной наукой и исследованиями в области фундаментальной физики.
2. **nica.jinr.ru** — информационный ресурс, посвященный проекту NICA (Nuclotron-based Ion Collider fAcility), реализуемому в ОИЯИ (Объединённом институте ядерных исследований).
3. **discuss-science.ru** — дискуссионный портал для обмена научными идеями и обсуждения исследовательских проектов.
4. **jinr.ru** — официальный сайт ОИЯИ, международной исследовательской организации, занимающейся ядерной физикой и смежными областями.
5. **lbl.gov** — сайт Лоуренс Беркли национальной лаборатории, ключевого учреждения для фундаментальных и прикладных исследований.
6. **ihep.su** — ресурс Института физики высоких энергий, посвящённый научным проектам в области физики элементарных частиц.
7. **home.cern** — официальный сайт Европейской организации по ядерным исследованиям (CERN), одного из крупнейших мировых центров физики элементарных частиц.

## Методология

1. **Оценка архивируемости**
   Для каждого сайта была проведена проверка на соответствие стандартам архивирования с использованием инструмента `ArchiveReady`. Полученные результаты включают метрику `CLEAR`, которая определяет уровень доступности и корректности веб-ресурса для сохранения.

2. **Сохранение данных**
   Архивирование сайтов осуществлялось с помощью утилиты командной строки `wpull`. Этот инструмент позволяет гибко настраивать параметры загрузки, включая глубину рекурсии, таймауты и сохранение метаданных. Для автоматизации массовой загрузки был написан Python-скрипт, использующий `wpull` (пример см. в репозитории).

3. **Анализ метаданных**
   Полученные архивы были проанализированы с помощью библиотеки `metawarc`, которая предоставляет функционал для обработки и извлечения метаданных из WARC-файлов.

4. **Воспроизведение архивов**
   Для проверки работоспособности архивов использовался сервис `ReplayWeb.page`, обеспечивающий удобный доступ к сохраненным веб-ресурсам.

## Итоги работы

В процессе работы удалось создать коллекцию объёмом XX Гб, состоящую из архивов 7 сайтов. Общая продолжительность скачивания составила XX часов. Сбор данных прошёл без существенных технических проблем.

Эта коллекция может быть полезной для исследователей, занимающихся изучением научной коммуникации, анализом крупных научных проектов и архивированием данных для цифровой гуманитаристики.

## Контакты
[Ваше имя], ЦМГН ВШЭ, 2024

## Условия использования
Данная работа распространяется под лицензией `CC0 1.0 Universal`.



# Коллекция WARC-архивов веб-сайтов

## Описание коллекции веб-сайтов

### Перечень сайтов:
1. **kino-teatr.ru**  
   Платформа, посвящённая киноиндустрии и театральному искусству. Содержит обширную базу данных фильмов, актёров, режиссёров и театров, а также отзывы, рейтинги и новостные статьи, связанные с миром искусства.

2. **sfy-conf.ru**  
   Сайт конференций и мероприятий, посвящённых теме науки и технологий будущего. Включает программы мероприятий, записи лекций, публикации исследований и списки участников.

3. **discuss-science.ru**  
   Научный форум, объединяющий исследователей, студентов и преподавателей для обсуждения актуальных вопросов науки, технологий и образовательных инициатив. Содержит статьи, обсуждения и тематические ветки.

4. **intermedia.ru**  
   Информационный портал, посвящённый событиям в мире музыки, кино, телевидения, театра и шоу-бизнеса. Публикует новости, обзоры, интервью и аналитические материалы для профессионалов и любителей индустрии развлечений.

---

## Цель коллекции
Коллекция сосредоточена на культуре, искусстве, образовании, науке, технологии и медиа. Данные могут быть полезны для:
- Исследования контента и тематического разнообразия сайтов.
- Выявления тенденций в создании онлайн-сообществ и платформ.
- Анализа структуры сайтов и их доступности для архивирования.

---

## Целевая аудитория
- Исследователи культуры, науки и технологий.
- Студенты, преподаватели и журналисты.
- Профессионалы в области искусства, медиа и кино.
- Любители межкультурного взаимодействия и научных обсуждений.

---

## Причина сохранения
- Создание архива контента.  
- Поддержка инициатив по сохранению культурного, научного и образовательного наследия в интернете.  
- Создание базы данных для дальнейших исследований в области цифровых гуманитарных наук.

---

## Используемые инструменты
1. **wpull**  
   Используется для скачивания веб-сайтов с сохранением всех необходимых файлов (HTML, CSS, изображения, скрипты и т.д.).

2. **WARC-файлы**  
   Содержат архивы скачанных страниц и ресурсов, обеспечивая их сохранность и пригодность для анализа.

3. **DB-файлы**  
   Хранят информацию о состоянии скачивания и структуре сайтов, упрощая навигацию внутри коллекции.

4. **Log-файлы**  
   Содержат логи процесса скачивания для диагностики ошибок и проверки полноты архивирования.

5. **CDX-файлы**  
   Индексируют содержимое WARC-файлов, позволяя быстро находить нужные ресурсы.

6. **metawarc**  
   Утилита для анализа WARC-архивов. Позволяет извлекать метаданные, анализировать содержимое и экспортировать данные для дальнейшего использования.

# Коллекция WARC-архивов веб-сайтов

## Описание
Данная коллекция включает веб-архивы следующих сайтов:
- **mnsfactory.ru** — сайт ...
- **lastseen.ru** — сайт ...

## Используемые технологии
- wpull
- sqlalchemy
- metawarc
## Автор
Кирилл Мезенев (inexy.plicable@gmail.com)

