Здесь объясняются опции, доступные при создании и настройке RSS:
  * **URL** — адрес записи. Каждый раз при вводе он проверяется на доступность, а страница проверяется на правильность формата.
  * **Импортировать в журнал**. Каждую ленту можно импортировать в любой из журналов и сообществ, в которые вы можете писать.
  * **Импортировать только записи с тегом** — если указана не пустая строка, то импортироваться будут только записи с указанным тегом. Остальные записи будут игнорироваться (но вы сможете проимпортировать их вручную). Если поле оставить пустым, будут импортироваться все найденные записи.
  * **Текст ссылки на источник** — если указан, к тексту импортированной записи добавляется ссылка на эту запись на сайте-источнике.
  * **Включить автоимпорт** — если галочка поставлена, робот будет индексировать ленту с интервалом в несколько минут и импортировать найденные записи.
  * **Добавлять тег `<noindex>`** — если галочка поставлена, текст импортируемой записи будет оборачиваться в тег `<noindex>`, содержимое которого не индексируется поисковиками. В противном случае поисковые машины, обнаружив дублирующийся контент, могут снизить рейтинг вашего сайта. Чтобы отлючить эту опцию, обратитесь в [техподдержку](Support.md) (не забудьте указать ЖЖ-логин). Так сделано для защиты от спамеров.
  * **Существующие записи: импортировать сейчас** — после нажатия кнопки «Сохранить» RSS-лента будет загружена, а все найденные записи будут проимпортированы в соответствии с указанными параметрами.
  * **Существующие записи: игнорировать** — найденные записи будут добавлены в таблицу статистики, но не импортируются (это действие идентично [действию кнопки «обновить»](Feed_actions.md)). Вы сможете вручную выбрать, какие из записей следует импортировать.