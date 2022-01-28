# myQA
Здесь кое-что для меня <br> 
<p>Искал информацию по поводу пользовательских сценариев, на русском языке ничего особо вразумительного и "на пальцах" не находил.
Забил в Гугле "use case example" и по первой <a href="https://www.usability.gov/how-to-and-tools/methods/use-cases.html">ссылке</a> нашел такое объяснение <b>use case</b> на пальцах.</p>
<p>Перевод автоматом, но всё равно понятно. Пример основан на работе стирки белья)))</p>
<h1>Случаи применения</h1>
<p>Вариант использования — это письменное описание того, как пользователи будут выполнять задачи на вашем веб-сайте. Он описывает, с точки зрения пользователя, поведение системы в ответ на запрос. Каждый вариант использования представлен как последовательность простых шагов, начиная с цели пользователя и заканчивая достижением этой цели.</p>
<h2>Преимущества вариантов использования</h2>
<p>Варианты использования добавляют ценность, потому что они помогают объяснить, как должна вести себя система, и в процессе они также помогают провести мозговой штурм, что может пойти не так. Они предоставляют список целей, и этот список можно использовать для определения стоимости и сложности системы. Затем проектные группы могут договориться о том, какие функции станут <a href="https://www.usability.gov/how-to-and-tools/methods/requirements.html">требованиями</a>   и будут построены.</p>
<table><tbody><tr><th scope="col">
				Какие варианты использования включают</th>
<th scope="col">
				Какие варианты использования НЕ включают</th>
</tr><tr><td>
<ul><li>
						Кто использует сайт</li>
<li>
						Что пользователь хочет сделать</li>
<li>
						Цель пользователя</li>
<li>
						Шаги, которые пользователь предпринимает для выполнения конкретной задачи</li>
<li>
						Как сайт должен реагировать на действие</li>
</ul></td><td>
<ul><li>
						Язык реализации</li>
<li>
						Подробная информация о пользовательских интерфейсах или экранах.</li>
</ul></td>
</tr></tbody></table>
<h2>Элементы варианта использования</h2>
<p>В зависимости от того, насколько глубоко и сложно вы хотите или должны получить, варианты использования описывают комбинацию следующих элементов:</p>
<ul><li>
		<strong>Actor - Актер</strong> – кто-либо или что-либо, кто выполняет какое-либо поведение (кто использует систему)</li>
<li>
		<strong>Stakeholder - Заинтересованное лицо</strong> – кто-то или что-то, заинтересованное в поведении обсуждаемой системы (SUD).</li>
<li>
		<strong>Primary Actor - Основное действующее лицо</strong> – заинтересованное лицо, которое инициирует взаимодействие с системой для достижения цели.</li>
<li>
		<strong>Preconditions - Предварительные условия</strong> –  что должно быть истинным или произойти до и после запуска варианта использования.</li>
<li>
		<strong>Triggers - Триггеры</strong> – это событие, которое приводит к запуску варианта использования.</li>
<li>
		<strong>Main success scenarios - Основные сценарии успеха </strong>[Basic Flow] – вариант использования, в котором все идет не так, как надо.</li>
<li>
		<strong>Alternative paths - Альтернативные пути </strong>[Alternative Flow] – эти пути являются вариацией на основную тему. Эти исключения возникают, когда что-то идет не так на системном уровне.</li>
</ul>

<h2>Как написать сценарий использования</h2>

<p>Запишите шаги варианта использования в понятном повествовании. <strong>Kenworthy (1997)</strong> выделяет следующие шаги:</p>
<ol>
	<li>
		Определите, кто будет пользоваться сайтом.</li>
<li>
		Выберите одного из этих пользователей.</li>
<li>
		Определите, что этот пользователь хочет делать на сайте. Каждая вещь, которую пользователь делает на сайте, становится вариантом использования.</li>
<li>
		Для каждого варианта использования определите нормальный ход событий, когда этот пользователь использует сайт.</li>
<li>
		Опишите базовый курс в описании варианта использования. Опишите это с точки зрения того, что делает пользователь и что делает система в ответ, о чем пользователь должен знать.</li>
<li>
		При описании основного курса рассмотрите альтернативные варианты развития событий и добавьте их, чтобы «расширить» вариант использования.</li>
<li>
		Ищите общие черты среди вариантов использования. Извлеките их и отметьте как распространенные варианты использования курса.</li>
<li>
		Повторите шаги с 2 по 7 для всех остальных пользователей.</li>
</ol>

<h2>Примеры использования</h2>

<p>Ниже приведены примеры трех вариантов использования с возрастающими уровнями сложности. Для наших целей мы определили их как простой, средний и тяжелый вариант использования для стирки. В каждом из этих типов вариантов использования вы увидите, что:</p>

<ul>
	<li>Домработница стирает в среду</li>
	<li>Она моет каждую партию.</li>
	<li>Она сушит каждую загрузку.</li>
<li>
		Она складывает определенные предметы.</li>
<li>
		Она гладит некоторые вещи.</li>
<li>
		Она выбрасывает определенные предметы.</li>
</ul>
<h3>
	Простой пример использования прачечной</h3>
<table><tbody><tr><th align="right" scope="row">
				<strong>Вариант использования 1</strong></th>
<td>
				Стирать</td>
</tr><tr><th align="right" scope="row">
				<strong>Actor - Актер</strong></th>
<td>
				Домработница</td>
</tr><tr><th align="right" scope="row">
				<strong>Basic Flow - Основной поток</strong></th>
<td>
				По средам экономка отчитывается в прачечной. Она сортирует белье, которое там есть. Затем она стирает каждую партию. Она сушит каждую загрузку. Она складывает предметы, которые нужно сложить. Она гладит и развешивает помятые вещи. Она выбрасывает любую вещь из белья, которая безвозвратно села, испачкалась или обгорела.</td>
</tr></tbody></table><h3>
	Пример использования прачечной среднего веса
Основной поток</h3>
<table><tbody><tr><th align="right" scope="row">
				<strong>Use Case 1 - Вариант использования 1</strong></th>
<td>
				Стирать</td>
</tr><tr><th align="right" scope="row">
				<strong>Actor</strong></th>
<td>
				Домработница</td>
</tr><tr><p>				<strong>Basic Flow</strong>
</p><td>
				По средам экономка отчитывается в прачечной. Она сортирует белье, которое там есть. Затем она стирает каждую партию. Она сушит каждую загрузку. Она складывает предметы, которые нужно сложить. Она выбрасывает любую вещь из белья, которая безвозвратно села, испачкалась или обгорела.</td>
</tr><tr><th align="right" scope="row">
				<strong>Alternative Flow 1</strong></th>
<td>
				Если она замечает, что что-то помялось, она гладит это, а затем вешает на вешалку.</td>
</tr><tr><th align="right" scope="row">
				<strong>Alternative Flow 2</strong></th>
<td>
				Если она замечает, что что-то все еще грязное, она перестирывает это.</td>
</tr><tr><th align="right" scope="row">
				<strong>Alternative Flow 3</strong></th>
<td>
				Если она замечает, что что-то сжалось, она выбрасывает это.</td>
</tr></tbody></table><h3>
	Пример использования тяжелой прачечной</h3>
<table><tbody><tr><th align="right" scope="row">
				<strong>Use Case 1</strong></th>
<td>
				Домработница занимается стиркой</td>
</tr><tr><th align="right" scope="row">
				<strong>Actor</strong></th>
<td>
				Домработница</td>
</tr><tr><th align="right" scope="row">
				<strong>Use Case Overview - Обзор варианта использования</strong></th>
<td>
				Сейчас среда, и в прачечной есть белье. Горничная сортирует его, а затем приступает к стирке каждой загрузки. Она складывает сухое белье, вынимая его из сушилки. Она гладит те вещи, которые нуждаются в глажке.</td>
</tr><tr><th align="right" scope="row">
				<strong>Subject Area - Предметная область</strong></th>
<td>
				Домашние</td>
</tr><tr><th align="right" scope="row">
				<strong>Actor(s)</strong></th>
<td>
				Домработница</td>
</tr><tr><th align="right" scope="row">
				<strong>Trigger</strong></th>
<td>
				Грязное белье доставляется в прачечную в среду.</td>
</tr><tr><th align="right" scope="row">
				<strong>Precondition 1</strong></th>
<td>
				Это среда.</td>
</tr><tr><th align="right" scope="row">
				<strong>Precondition 2</strong></th>
<td>
				В прачечной есть белье.</td>
</tr></tbody></table><h4>
	<strong>Basic Flow: Do Laundry - Основной поток: стирка</strong></h4>
<table><tbody><tr><th align="right" scope="row">
				<strong>Description - Описание</strong></th>
<td>
				Этот сценарий описывает ситуацию, когда требуется только сортировка, стирка и складывание. Это основной сценарий успеха.</td>
</tr><tr><th align="right" scope="row">
				<strong>1</strong></th>
<td>
				Домработница сортирует белье.</td>
</tr><tr><th align="right" scope="row">
				<strong>2</strong></th>
<td>
				Домработница моет каждую партию.</td>
</tr><tr><th align="right" scope="row">
				<strong>3</strong></th>
<td>
				Домработница сушит каждую загрузку.</td>
</tr><tr><th align="right" scope="row">
				<strong>4</strong></th>
<td>
				Домработница проверяет, что белье не нуждается в глажке, чистое и не севшее.</td>
</tr><tr><th align="right" scope="row">
				<strong>5</strong></th>
<td>
				Домработница проверяет, можно ли сложить белье.</td>
</tr><tr><th align="right" scope="row">
				<strong>6</strong></th>
<td>
				Домработница складывает белье.</td>
</tr><tr><th align="right" scope="row">
				<strong>7</strong></th>
<td>
				Домработница делает это до тех пор, пока не закончатся вещи для стирки.</td>
</tr><tr><th align="right" scope="row">
				<strong>Termination outcome - Исход прекращения</strong></th>
<td>
				Белье чистое и сложенное.</td>
</tr></tbody></table><h4>
	<strong>Alternative Flow 4A: Белье нужно погладить.</strong></h4>
<table><tbody><tr><th align="right" scope="row">
				<strong>Description</strong></th>
<td>
				Этот сценарий описывает ситуацию, когда одну или несколько вещей необходимо погладить перед складыванием или вместо него.</td>
</tr><tr><th align="right" scope="row">
				<strong>4A1</strong></th>
<td>
				Домработница проверяет, нужно ли гладить белье, чтобы оно было чистым и не село.</td>
</tr><tr><th align="right" scope="row">
				<strong>4A2</strong></th>
<td>
				Домработница гладит белье.</td>
</tr><tr><th align="right" scope="row">
				<strong>4A3</strong></th>
<td>
				Домработница кладет белье на вешалку.</td>
</tr><tr><th align="right" scope="row">
				<strong>Termination outcome - Исход прекращения</strong></th>
<td>
				Белье, которое нужно погладить, гладят и развешивают.</td>
</tr></tbody></table><h4>
	<strong>Alternative flow 4B: Белье грязное.</strong></h4>
<table><tbody><tr><th align="right" scope="row">
				<strong>Description</strong></th>
<td>
				Этот сценарий описывает ситуацию, когда белье не стало чистым после первой стирки.</td>
</tr><tr><th align="right" scope="row">
				<strong>4B1</strong></th>
<td>
				Housekeeper verifies that the laundry item is not clean.</td>
</tr><tr><th align="right" scope="row">
				<strong>4B2</strong></th>
<td>
				Housekeeper rewashes the laundry item</td>
</tr><tr><th align="right" scope="row">
				<strong>Termination outcome</strong></th>
<td>
				Dirty laundry is rewashed.</td>
</tr></tbody></table><h4>
	<strong>Alternative flow 4C: Laundry item shrank.</strong></h4>
<table><tbody><tr><th align="right" scope="row">
				<strong>Description</strong></th>
<td>
				This scenario describes the situation where the laundry item shrank.</td>
</tr><tr><th align="right" scope="row">
				<strong>4C1</strong></th>
<td>
				Housekeeper verifies that the laundry item shrank</td>
</tr><tr><th align="right" scope="row">
				<strong>4C2</strong></th>
<td>
				Housekeeper disposes of laundry item.</td>
</tr><tr><th align="right" scope="row">
				<strong>Termination outcome</strong></th>
<td>
				Laundry item no longer exists.</td>
</tr></tbody></table><h4>
	<strong>Alternative flow 5A: Laundry item needs hanger.</strong></h4>
<table><tbody><tr><th align="right" scope="row">
				<strong>Description</strong></th>
<td>
				This scenario describes the situation where the laundry item needs to be hung instead of folded.</td>
</tr><tr><th align="right" scope="row">
				<strong>5A1</strong></th>
<td>
				Housekeeper verifies that laundry item needs hanging.</td>
</tr><tr><th align="right" scope="row">
				<strong>5A2</strong></th>
<td>
				Housekeeper puts laundry item on a hanger.</td>
</tr><tr><th align="right" scope="row">
				<strong>Termination outcome</strong></th>
<td>
				Laundry that needs hanging is hung up.</td>
</tr></tbody></table><p><strong>Post conditions:</strong> All laundry clean and folded or hung up.</p>
<p><strong>Business Rules:</strong></p>
<ul><li>
		Laundry can only be done on Wednesdays.</li>
<li>
		All ironed laundry items get hung on hangers</li>
<li>
		Any laundry item that is irrevocably soiled, shrunken, scorched, etc. , gets thrown out.</li>
</ul></div></div></div>
