# День IT-знаний 2022 «ВИДЕОТЕХНОЛОГИИ»

---

## Вступление и знакомство

### Слайды 1 и 2

Представьтесь и расскажите, чем занимаетесь: ваша
профессия и команда, какие сервисы или продукты
создаете.

>Как вы думаете, какой объем видео сейчас хранится
в интернете?

Понадобится примерно 7 лет, чтобы посмотреть
только тот объем видео, который передается по
всему миру в сети каждую секунду
Источник: Cisco System, 2021

## Основная часть. «Про видео: как это устроено»

### Слайд 3

На этой встрече мы будем говорить о видеотехнологиях.

>В каких сферах используется видеотехнологии и каким образом?

- образование - учебные онлайн-занятия, видеокурсы
- медицина - консультации, для дистанционной хирургии
- коммерция - онлайн-тренировки, AR-примерочные, покупки
  в режиме реального времени через видео и пр.
- безопасность - видеонаблюдение, интернет вещей и умный дом,
  видеоняни и пр.
- спорт - видеофиксация, AR для тренировок
- видеоигры

Для вас есть первое задание.

>Попробуйте подсчитать, сколько видеороликов сегодня вы увидели,
перед нашей встречи?

В нашей жизни видеотехнологии повсюду.

### Слайды 4, 5, 6, 7, 8

- я смотрю новости и почти в каждой есть видео
- листаю социальные сети, там видеоролики и клипы
- могу позаниматься спортом, повторяя упражнения в записи
- на работе, видео звонки
- вечером, приготовить ужин с помощью видеорецепта
- уделить время учебе и посмотреть свежий онлайн-курс

Кстати, очень удобно, когда можно продолжать просмотр на
разных устройствах.

### Слайд 9

Сегодня вы узнаете, как именно это происходит.
Мы затронем разные стороны:

- Как по воздуху прилетает видео?
- Почему видео зависает?
- Как связаны математика и успех блогеров?

Это небольшая часть вопросов, на которые будем вместе
сегодня искать ответы.

### Слайд 10

Как выглядит классный видеосервис
со стороны пользователей, то есть нас с вами?

Включаешь видео — и получаешь удовольствие от
просмотра.

### Слайд 11

А, вот как выглядит с точки зрения технологий?

Посмотрим на архитектуру видеоплатформы:

- пользователи загружают видео на сервера,
- оно обрабатывается и преобразуется в разные форматы и
  разрешения,
- потом сохраняется в большом распределённом хранилище и
  оттуда раздаётся зрителям.

Так работают как видеоплатформы с небольшим набором функций,
так и видеогиганты. Например, Youtbe или `VK Видео`.

Давайте вернемся на один шаг и посмотрим, что именно
загружает пользователь в сеть, и откуда у видео появляется `вес`?

### Слайд 12

Видео — это быстро сменяющие друг друга кадры на
определенной скорости. Именно набор картинок мы и называем видео.

>На слайде изображен `кинеограф` — это прибор для создания
анимированных изображений.

### Слайд 13

Чтобы представить себе, что такое цифровое видео,
возьмем набор изображений, которые расположились в
нужном нам порядке и сняты с определенной частотой
(например, 30 кадров в секунду).

>Чем больше кадров в секунду воспроизводится, тем плавнее
и реалистичнее видео. При низких значения FPS
происходит то самое «зависание».

### Слайд 14

Что такое изображение? — это набор маленьких точек
известных как пиксели. Каждый из пикселей содержит
закодированную информацию о цвете.

В копьютерах, в основном используется кодировка RGB
(red green blue).

>Давайте посчитаем, каким был бы размер (вес) 10-секундного
видео с 60 fps без сжатия в качестве Full HD.

>Кто-то может прикинуть в уме, сколько это будет?

### Слайд 15

Ладно, есть готовый ответ.

`1920 * 1080 * 3 байта (=24 бита) * 10 с * 60 fps = 3,4 ГБ`

>3,4 ГБ — такой вес для 10-секундного видео неприемлемый.

### Слайд 16

Чтобы решить эту проблему используют кодеки —
программы, которые сжимают файлы для передачи и
последующего просмотра.

>Кодеком может называться как программа, так и набор
правил трансформации файла.

С кодеком вес видео может уменьшиться в 850 раз!

После таких преобразований вместо 10 секунд в 3,4 ГБ
памяти помещается полноценный фильм.

Кодек учитывает, что соседние кадры, как правило,
незначительно отличаются друг от друга. Поэтому в
видео находится ключевой кадр, а дальше кодируется
только информация, которая меняется.

Кодек помогает сжать цифровые данные и получить из
3,4 ГБ необработанного видео файл весом всего 4 МБ.

Без видеокодеков не было бы доступных пользователям
видеоплатформ, стриминга и видеозвонков.

>С обычными роликами разобрались, теперь продолжим
про особенности видео связи. Технически это совсем
непростая штука.

### Слайд 17

Особенности видео связи

- Как сделать так, чтобы собеседники слышали и видели
друг друга в лучшем качестве?
- А если созваниваются не два человека, а десять или
несколько тысяч?
- А ещё все они звонят с разных мест, с разных устройств:
кто-то из браузера на ноутбуке, кто-то с телефона, кто-то с
планшета?

Задача, действительно, сложная.

### Слайд 18

Из-за пандемии в начале 2020 года, все очень быстро
перешли в онлайн. Потребовалось совершенно другое
качество видеосвязи, для общения с близкими, для
учебы и работы.

Люди стали предъявляют высокие требования к видеосвязи.

>Как думаете, какие это могут быть пожелания?

### Слайд 19

Бывает, что нужно созвониться на двоих, а иногда собрать
группу или провести онлайн-мероприятие на большое количество людей.

>Ограничений по количеству участников быть не должно.
И при этом хочется, чтобы все могли подключаться с видео,
а не просто смотреть на других.

Когда спикер включает демонстрацию экрана
(по-другому — шеринг экрана) с презентацией, нужно, чтобы
качество картинки было очень чётким, в формате 4К. А на
небольшом экране смартфона слайд можно было бы
приблизить с помощью зума.

И чтобы звонки работали на любых платформах и устройствах
в условиях мобильного нестабильного интернета.

>Удобство интерфейса и дополнительные фишки
беспокоят пользователей гораздо меньше, чем
качество.

### Слайд 20

Теперь переведем с языка пользователей на
язык бизнес-требований. Обычно этим занимаются
продакт-менеджеры.

Вот что примерно получится, если мы поставим задачу
для разработчиков на создание сервиса, под кодовым
названием «крутые видеозвонки»:

- неограниченное число участников;
- работа на всех платформах (мобильные и
  десктопы);
- низкое потребление серверных ресурсов;
- высокое качество
- низкое потребление ресурсов на
  пользовательских устройствах — чтобы качество
  было высоким для пользователей с разными
  возможностями устройства по техническим
  характеристикам, не садило быстро аккумулятор.

### Слайд 21

Дальше команда разработки приступает к реализации.

>Как видеозвонок происходит технически?

Есть сервер сигналинга (signaling), он позволяет
обнаружить других участников звонка, то есть
идентифицировать друг друга в интернете и начать
прямое соединение.

>Когда два знакомых нам героя решают поболтать. Один
звонит другому и в этот момент отправляет запрос через
сервер сигналинга, посылая свой набор настроек – так
называемый «пакет», где есть видеокодеки, скорость
интернета, IP-адреса. Когда другой пользователь
принимает видеовызов, он в ответ отправляет такой же
«пакет», но уже со своими настройками.

### Слайд 22

В момент, когда на сервере сигналинга находятся оба
пакета с настройками, сервер перебрасывает пакеты
пользователей друг другу.

После этого между ними уже происходит прямое
соединение. В этот момент сервер сигналинга выходит из
игры и пользователи спокойно общаются.

### Слайд 23

Кстати, чем чаще вы с другим пользователем
созваниваетесь по видео, тем сервис быстрее угадывает,
какие нужны настройки. Почему так?

Здесь в игру вступает нейронные сети.

>Неросети часто путают с искуственным интелектом.

Их так называют из-за схожести работы
математической модели с функционированием нервной
системы человека.

Искусственные нейроны, объединенные в сеть и
обученные обрабатывать огромное количество входных
сигналов по определенному алгоритму, способны быстро выдавать
результат.
Нейросети лучше других алгоритмов сейчас
справляются со сложно структурированными данными, а
это как раз и есть видео, картинки и тексты. Про это мы
ещё сегодня успеем поговорить.

Так вот, если часто звонить друг другу в VK Звонках, то
нейросеть будет обрабатывать запросы и собирать
необходимые данные — запоминать локации и те самые
«пакеты» пользователей, делая их подстройку между
собой более качественной.

Основные области применения нейронных сетей:

- прогнозирование,
- распознавание образов,
- оптимизация,
- анализ данных,
- генерация изображений и текстов.

>Неросети становится незаменимым
помощником в развитии видеозвонков, вот ещё
несколько примеров его применения:

- выделения речи человека из шума или тишины;
- шумоподавление;
- улучшение изображения, лица;
- оценка качества звонков.

### Слайд 24

Каждый из вас может протестировать, насколько хорошо
алгоритмы справляются со своей задачей.

>Предлагаю попробовать себя в роли тестировщика
видеозвонков. Задержку в видео можно измерить с помощью
простого приёма. Создаем звонок и подключаемся с двух
устройств. Включаем секундомер и снимаем его.
Вместе фотографируем экран с исходящим видео и экран
принимающего клиента. Останется только сравнить
результат.

В IT-команде без `тестировщиков` никуда. Эти
специалисты проверяют качество и работоспособность
продукта, насколько он соответствует требованиям
пользователя. Тестировщик описывает, как выглядит
ошибка, в каких условиях возникает. Эта информация
помогает разработчикам улучшать продукт и быстрее
справляться с неполадками.
Современные тестировщики автоматизируют проверку и
пользуются для этого профессиональными инструментами.

(по-другому Quality assurance specialist или QA-инженер)

>Чем занимается тестировщик:

- тестирование продукта,
- поиск багов,
- подготовка отчетов,
- общение с разработчиками,
- работа с документацией.

## Основная часть. «Про искусственный интеллект в видеотехнологиях»

### Слайд 25

Кроме видеозвонков пользователи загружают в сеть
большое количество собственного контента, чтобы
делиться своими идеями и находить единомышленников.

Мы уже немного узнали про методы "искусственного
интеллекта" в видеозвонках. Посмотрим и другие
варианты его использования.

### Слайд 26

Как "искусственный интеллект" помогает пользователям и
авторам создавать классный контент?

Сначала вспомним про `AR-эффекты` и `дополненную реальность`.

В звонках, клипах и трансляциях можно поменять
стандартный фон за своей спиной на виртуальный.
Он может быть и статичным, и анимационным. С точки
зрения технологии здесь работают нейросети: они
распознают фигуру человека и строят его точный контур,
а потом быстро отрисовывают текстуры для замены
фона.

>Пользователь может двигаться во время вызова и не
переживать, что собеседники заметят обстановку позади
него. Виртуальный фон помогает создать нужное
настроение: праздничное или рабочее, какое необходимо
здесь и сейчас. Можно использовать предлагаемые фоны
или загружать свои.

### Слайд 27

Ещё одна многими любимая технология — `маски`. Их
можно использовать как в видеозвонках, так и для записи
видео.

>Маски быстро дополняют образ забавными деталями и
дают возможность перевоплотиться в любимого
персонажа.

Чтобы маска удачно работала, применяют
технологию распознавания лица. Для этого также
используют нейросеть, она определяет, где глаза, нос,
уши у человека. При этом хороший алгоритм будет
одинаково классно работать в разных условиях. Даже
если в помещении будет плохой свет, человек в очках и
он наклонил голову в кадре.

### Слайд 28

Не только люди могут преобразиться, наши любимые
питомцы тоже могут попробовать примерить маску для
котов.

>Задача по распознаванию мордочки кота или кошки
совсем непростая, к распознаванию добавляются усы, а
форм головы и ушей гораздо больше, чем у человека. Но
алгоритмы VK справляются. Чтобы нейронная сеть
распознавала питомца, её обучили на 10 тысячах
изображений котов и кошек разных пород. Нейросеть
предсказывает ориентацию головы животного — на
основе этой информации трёхмерная модель маски
позиционируется, визуализируется и накладывается на
исходный кадр.

>Котики благодаря маскам способны перевоплотиться в
героев вирусных видео — персонажей мемов и аниме.
Выбрать парик, шляпку, повязку пирата, косички или
бигуди.

### Слайд 29

Вот вы сняли видео на виртуальном фоне с котом в
маске и решили поделиться с друзьями, но качество вас
не устраивает. Что делать? Тут тоже поможет
"искусственный интеллект" и технология `NeuroHD`.

`NeuroHD` преображает видео и улучшает его качество
благодаря нейросети. В результате 40 млн пользователей
`VK Видео` смогут увидеть ваш ролик в повышенном
разрешении, даже если изначально его качество было
низким.

В основе `NeuroHD` — продвинутая нейросеть из
семейства генеративно-состязательных сетей (GAN).
Принцип работы таких нейросетей заключается в том, что
при их обучении используется две модели. Одна из них
генерирует увеличенные изображения (кадры), а другая
— проверяет, чтобы сгенерированные изображения не
отличались от исходных.

>С помощью нейросети `NeuroHD` можно повысить
разрешение до 720р, частоту кадров до 60 FPS.

### Слайд 30

Про создание видео поговорили, а как "искусственный
интеллект" помогает каждому из нас получать классный
пользовательский опыт?

Почти за каждой кнопкой интерфейса витрины `VK Видео`,
`VK Клипов`, `TikTok`, а также `Youtube` скрывается
машинное обучение.

Вкладка _«Для вас»_ — это ваши персональные
рекомендации. Контента вокруг сейчас очень много и без
рекомендаций невозможно представить ни один
продвинутый сервис. Откуда видеоплатформа знает, что
вам понравятся эти видео и клипы?

>Чтобы угадывать интересы пользователя, на
большинстве крупных видеоплатформ используют
рекомендательные системы. Это математический
алгоритм, который учитывает огромное количество
данных:

- что вы лайкаете,
- на кого вы подписаны,
- что смотрят люди, похожие на вас по профилю,
- как долго вы смотрите конкретные видео,
- как быстро переключаетесь между клипами и так далее.

>Чем больше времени вы пользуетесь сервисом и
взаимодействуете с контентом, тем лучше алгоритмы
понимают, что вам интересно и что из контента стоит
предложить.

### Слайд 31

Рекомендательные системы, как и другие алгоритмы
"искусственного интеллекта", создаются `Data Scientist’ами`
(исследователями данных). Если обобщить, то это
специалисты, которые разрабатывают программы для
анализа массивов сложных данных и помогают таким
образом решать бизнес-задачи.

>В том числе `Data Scientist’ы` разрабатывают десятки
нейросетей, которые способны проанализировать видео
сразу при загрузке.

На видео распознаются отдельные элементы и признаки,
происходит тегирование. Если набор тегов совпадет с
интересами пользователя, то алгоритм порекомендует
ему это видео.

Схожая профессия с исследователем данных — это `ML-разработчик`.
Эти специалисты совершенствуют код и находят способы
решения бизнес-задач при помощи машинного обучения.

### Слайд 32

Чаще всего про рекомендации мы слышим, когда говорим
о Клипах и видеороликах.

>Какой блогер не мечтает попасть в тренд? ;-)

Получается, чтобы ролик попал в тренд, надо разобраться в
математике алгоритмов.

Вот как выглядит стандартная жизнь видеоролика:

- Автор снимает и загружает ролик.
- Нейросети анализируют, что на видео, назначает ролику
  определенные теги.
- Затем к модерации видео подключаются живые люди —
  модераторы. Они определяют, можно ли показывать клип
  на широкую аудиторию с точки зрения допустимого контента.
- Дальше в дело вступают алгоритмы продвижения новых клипов.

И вот, миллион просмотров уже близко!

### Слайд 33

Мы увидели, что "искусственный интеллект" отлично
справляется с распознаванием изображений. Как дела
обстоят с текстом?

Автоматические субтитры генерируются в четыре этапа.

1. В видеоплеере используется нейросеть, которая сначала
распознает речь человека среди посторонних шумов.

2. Затем распознает отдельные слова и формирует из них
текст.

3. Потом подключается ещё один алгоритм, чтобы
расставить знаки препинания и заглавные буквы.

4. Завершающий этап — методы машинного обучения
распределяют текст по кадрам, чтобы фраза появлялась
точно в момент, когда говорящий её произносит.

>Чем-то всё это напоминает процесс записи диктанта, а
ведь так и есть — нейросеть перед тем, как создавать
автоматические субтитры, обучается и тренируется на
большом количестве видеозаписей.

## Основная часть. «Про профессии и возможности в IT»

### Слайд 34

Мы затронули несколько профессий, представители
которых занимаются видеотехнологиями. Но какую бы
профессию в IT вы ни выбрали, это перспективная и
интересная отрасль. К началу осени этого года на самом
известном карьерном сайте было размещено 63 тысячи
вакансий из IT-сферы!

Сотрудники IT-компаний работают в комфортных
условиях и получают большое количество бонусов.

### Слайд 35

>Хотите попробовать себя в качестве IT-специалиста
прямо сейчас?

Попробуйте «Тест-драйв IT-профессий». С помощью
специально чат-бота вы сможете познакомиться
с разными IT-профессиями и уже попробовать
на себе их задачи.

>Вы можете попробовать сделать это прямо сейчас или дома.

### Слайд 36

ответы на вопросы
