<a name="readme-top"></a>

<details>
	<summary>Вопросы</summary>
	<ol>
		<li><a href="#l-value-%D0%B8-r-value">l-value и r-value</a></li>
		<li><a href="#nullptr-null-0">nullptr, null, 0</a></li>
		<li><a href="#%D0%B0%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC-%D0%B1%D0%B8%D0%BD%D0%B0%D1%80%D0%BD%D0%BE%D0%B3%D0%BE-%D0%BF%D0%BE%D0%B8%D1%81%D0%BA%D0%B0">Алгоритм бинарного поиска</a></li>
		<li><a href="#%D0%B0%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC-%D1%81%D0%BE%D1%80%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B8-%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D1%8B%D0%B5-%D1%85%D0%B0%D1%80%D0%B0%D0%BA%D1%82%D0%B5%D1%80%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B8">Алгоритм сортировки, основные характеристики</a></li>
		<li><a href="#%D0%B0%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC-%D1%85%D0%B5%D1%88%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F">Алгоритм хеширования</a></li>
		<li><a href="#%D0%B0%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC%D1%8B-%D1%81%D1%82%D0%B0%D0%BD%D0%B4%D0%B0%D1%80%D1%82%D0%BD%D0%BE%D0%B9-%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B8">Алгоритмы стандартной библиотеки</a></li>
		<li><a href="#%D0%B0%D0%BB%D1%84%D0%B0%D0%B2%D0%B8%D1%82-%D0%B8-%D0%B8%D0%B4%D0%B5%D0%BD%D1%82%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%82%D0%BE%D1%80">Алфавит и идентификатор</a></li>
		<li><a href="#%D0%B0%D1%80%D0%B8%D1%84%D0%BC%D0%B5%D1%82%D0%B8%D0%BA%D0%B0-%D1%83%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9">Арифметика указателей</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4">Атд</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%ABc%D1%82%D0%B5%D0%BA%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «cтек» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%AB%D0%B4%D1%8D%D0%BA%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «дэк» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%AB%D0%BC%D0%B0%D1%81%D1%81%D0%B8%D0%B2%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «массив» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%AB%D0%BC%D0%B0%D1%82%D1%80%D0%B8%D1%86%D0%B0%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «матрица» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%AB%D0%BC%D0%BD%D0%BE%D0%B6%D0%B5%D1%81%D1%82%D0%B2%D0%BE%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «множество» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%AB%D0%BE%D1%87%D0%B5%D1%80%D0%B5%D0%B4%D1%8C-%D1%81-%D0%BF%D1%80%D0%B8%D0%BE%D1%80%D0%B8%D1%82%D0%B5%D1%82%D0%BE%D0%BC%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «очередь с приоритетом» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%AB%D0%BE%D1%87%D0%B5%D1%80%D0%B5%D0%B4%D1%8C%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «очередь» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%AB%D0%BF%D0%BE%D0%BB%D0%B8%D0%BD%D0%BE%D0%BC%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «полином» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%AB%D1%81%D0%BB%D0%BE%D0%B2%D0%B0%D1%80%D1%8C%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «словарь» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%AB%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B0%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «строка» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%C2%AB%D1%87%D0%B8%D1%81%D0%BB%D0%BE%C2%BB-%D0%B8-%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82%D1%8B-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8">Атд «число» и варианты реализации</a></li>
		<li><a href="#%D0%B0%D1%82%D0%B4-%D0%B8-%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85">Атд и структура данных</a></li>
		<li><a href="#%D0%B1%D0%B5%D1%81%D0%BA%D0%BE%D0%BD%D0%B5%D1%87%D0%BD%D1%8B%D0%B5-%D1%86%D0%B8%D0%BA%D0%BB%D1%8B">Бесконечные циклы</a></li>
		<li><a href="#%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0-%28library%29-%D0%B8-%D0%BA%D0%B0%D1%80%D0%BA%D0%B0%D1%81-%28framework%29">Библиотека (library) и каркас (framework)</a></li>
		<li><a href="#%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0-%D0%B4%D0%B8%D0%BD%D0%B0%D0%BC%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F">Библиотека динамическая</a></li>
		<li><a href="#%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0-%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F">Библиотека статическая</a></li>
		<li><a href="#%D0%B1%D1%83%D1%84%D0%B5%D1%80%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-%D0%BF%D1%80%D0%B8-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B8-%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%BE%D0%B2">Буферизация при использовании потоков</a></li>
		<li><a href="#%D0%B2%D0%B0%D0%BB%D0%B8%D0%B4%D0%BD%D0%BE%D1%81%D1%82%D1%8C-%D0%B8%D1%82%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BE%D0%B2">Валидность итераторов</a></li>
		<li><a href="#%D0%B2%D0%B2%D0%BE%D0%B4-%D0%B8-%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4-%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0-%D0%BE%D1%88%D0%B8%D0%B1%D0%BE%D0%BA">Ввод и вывод, обработка ошибок</a></li>
		<li><a href="#%D0%B2%D0%B2%D0%BE%D0%B4-%D0%B8-%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4-%D1%81%D1%82%D0%B0%D0%BD%D0%B4%D0%B0%D1%80%D1%82%D0%BD%D0%B0%D1%8F-%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0">Ввод и вывод, стандартная библиотека</a></li>
		<li><a href="#%D0%B2%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9-%D0%BC%D0%B0%D1%81%D1%81%D0%B8%D0%B2">Встроенный массив</a></li>
		<li><a href="#%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4-%D0%B8-%D0%B2%D0%B2%D0%BE%D0%B4-%D0%BD%D0%B5%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D1%8B%D0%B9">Вывод и ввод, неформатированный</a></li>
		<li><a href="#%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4-%D0%B8-%D0%B2%D0%B2%D0%BE%D0%B4-%D0%BF%D0%BE%D0%B7%D0%B8%D1%86%D0%B8%D0%BE%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5">Вывод и ввод, позиционирование</a></li>
		<li><a href="#%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4-%D0%B8-%D0%B2%D0%B2%D0%BE%D0%B4-%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B8">Вывод и ввод, потоки</a></li>
		<li><a href="#%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4-%D0%B8-%D0%B2%D0%B2%D0%BE%D0%B4-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%D1%8B%D0%B5-%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B8">Вывод и ввод, файловые потоки</a></li>
		<li><a href="#%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4-%D0%B8-%D0%B2%D0%B2%D0%BE%D0%B4-%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D1%8B%D0%B9">Вывод и ввод, форматированный</a></li>
		<li><a href="#%D0%B2%D1%8B%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5">Выражение</a></li>
		<li><a href="#%D0%B2%D1%8B%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F---%D0%BF%D1%80%D0%B8%D0%BE%D1%80%D0%B8%D1%82%D0%B5%D1%82%D1%8B-%D0%B8-%D0%BF%D0%BE%D1%80%D1%8F%D0%B4%D0%BE%D0%BA-%D0%B2%D1%8B%D1%87%D0%B8%D1%81%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F">Выражения - приоритеты и порядок вычисления</a></li>
		<li><a href="#%D0%B3%D0%BB%D0%BE%D0%B1%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D0%B8-%D0%BB%D0%BE%D0%BA%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D0%B8%D0%BC%D0%B5%D0%BD%D0%B0">Глобальные и локальные имена</a></li>
		<li><a href="#%D0%B4%D0%B5%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D0%BE%D1%80">Деструктор</a></li>
		<li><a href="#%D0%B4%D0%B8%D0%B0%D0%BF%D0%B0%D0%B7%D0%BE%D0%BD%D1%8B-%D0%B0%D1%80%D0%B8%D1%84%D0%BC%D0%B5%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D1%85-%D1%82%D0%B8%D0%BF%D0%BE%D0%B2">Диапазоны арифметических типов</a></li>
		<li><a href="#%D0%B4%D0%B8%D0%B0%D0%BF%D0%B0%D0%B7%D0%BE%D0%BD%D1%8B-%D0%B8-%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%86%D0%B8%D0%B8-%D0%BD%D0%B0%D0%B4-%D0%BD%D0%B8%D0%BC%D0%B8">Диапазоны и операции над ними</a></li>
		<li><a href="#%D0%B4%D0%B8%D0%BD%D0%B0%D0%BC%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5-%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C%D1%8E">Динамическое управление памятью</a></li>
		<li><a href="#%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF-%D0%BA-%D0%B8%D0%BC%D0%B5%D0%BD%D0%B0%D0%BC-%D0%B2-%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D1%81%D1%82%D0%B2%D0%B5">Доступ к именам в пространстве</a></li>
		<li><a href="#%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF-%D0%BA-%D1%87%D0%BB%D0%B5%D0%BD%D0%B0%D0%BC">Доступ к членам</a></li>
		<li><a href="#%D0%B4%D1%80%D1%83%D0%B7%D1%8C%D1%8F-%28friend%29">Друзья (friend)</a></li>
		<li><a href="#%D0%B7%D0%B0%D0%B3%D0%BE%D0%BB%D0%BE%D0%B2%D0%BE%D1%87%D0%BD%D1%8B%D0%B5-%D1%84%D0%B0%D0%B9%D0%BB%D1%8B---%D0%BF%D1%80%D0%B0%D0%BA%D1%82%D0%B8%D0%BA%D0%B0-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F">Заголовочные файлы - практика использования</a></li>
		<li><a href="#%D0%B7%D0%B0%D0%BA%D0%BE%D0%BD-%D0%B4%D1%8B%D1%80%D1%8F%D0%B2%D1%8B%D1%85-%D0%B0%D0%B1%D1%81%D1%82%D1%80%D0%B0%D0%BA%D1%86%D0%B8%D0%B9">Закон дырявых абстракций</a></li>
		<li><a href="#%D0%B7%D0%B0%D0%BC%D0%B5%D1%89%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D0%B0">Замещение метода</a></li>
		<li><a href="#%D0%B8%D0%BD%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82-%D1%82%D0%B8%D0%BF%D0%B0">Инвариант типа</a></li>
		<li><a href="#%D0%B8%D0%BD%D0%B8%D1%86%D0%B8%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F">Инициализация</a></li>
		<li><a href="#%D0%B8%D0%BD%D0%BA%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D1%82-%D0%B8-%D0%B4%D0%B5%D0%BA%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D1%82">Инкремент и декремент</a></li>
		<li><a href="#%D0%B8%D0%BD%D1%81%D1%82%D0%B0%D0%BD%D1%86%D0%B8%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5">Инстанциирование</a></li>
		<li><a href="#%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D0%B8-%D0%B2%D1%8B%D0%B1%D0%BE%D1%80%D0%B0">Инструкции выбора</a></li>
		<li><a href="#%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D0%B8-%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F">Инструкции управления</a></li>
		<li><a href="#%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D0%B8-%D1%86%D0%B8%D0%BA%D0%BB%D0%BE%D0%B2">Инструкции циклов</a></li>
		<li><a href="#%D0%B8%D0%BD%D1%82%D0%B5%D0%B3%D1%80%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%B0%D1%8F-%D1%81%D1%80%D0%B5%D0%B4%D0%B0-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B8">Интегрированная среда разработки</a></li>
		<li><a href="#%D0%B8%D1%81%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B3%D0%B0%D1%80%D0%B0%D0%BD%D1%82%D0%B8%D0%B8-%D0%B1%D0%B5%D0%B7%D0%BE%D0%BF%D0%B0%D1%81%D0%BD%D0%BE%D1%81%D1%82%D0%B8">Исключения, гарантии безопасности</a></li>
		<li><a href="#%D0%B8%D1%81%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D1%8F-%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0">Исключения, обработка</a></li>
		<li><a href="#%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D0%B0%D1%80%D0%B0%D0%BC%D0%B5%D1%82%D1%80%D0%BE%D0%B2-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%BD%D0%BE%D0%B9-%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8">Использование параметров командной строки</a></li>
		<li><a href="#%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%B5%D0%BF%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%D0%BE%D1%80%D0%B0">Использование препроцессора</a></li>
		<li><a href="#%D0%B8%D1%82%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%28%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D1%8B%D0%B5-%D0%BF%D0%BE%D0%BD%D1%8F%D1%82%D0%B8%D1%8F-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%29">Итераторы (основные понятия, использование)</a></li>
		<li><a href="#%D0%B8%D1%82%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%D0%B0%D0%B4%D0%B0%D0%BF%D1%82%D0%B8%D1%80%D1%83%D1%8E%D1%89%D0%B8%D0%B5">Итераторы адаптирующие</a></li>
		<li><a href="#%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D1%8B-%D0%B8-%D1%8D%D0%BA%D0%B7%D0%B5%D0%BC%D0%BF%D0%BB%D1%8F%D1%80%D1%8B">Классы и экземпляры</a></li>
		<li><a href="#%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%B2%D0%BE%D0%B5-%D1%81%D0%BB%D0%BE%D0%B2%D0%BE-extern">Ключевое слово extern</a></li>
		<li><a href="#%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%B2%D0%BE%D0%B5-%D1%81%D0%BB%D0%BE%D0%B2%D0%BE-override">Ключевое слово override</a></li>
		<li><a href="#%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%B2%D0%BE%D0%B5-%D1%81%D0%BB%D0%BE%D0%B2%D0%BE-template-%D0%B8-typename">Ключевое слово template и typename</a></li>
		<li><a href="#%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%B2%D0%BE%D0%B5-%D1%81%D0%BB%D0%BE%D0%B2%D0%BE-this">Ключевое слово this</a></li>
		<li><a href="#%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%B2%D0%BE%D0%B5-%D1%81%D0%BB%D0%BE%D0%B2%D0%BE-using">Ключевое слово using</a></li>
		<li><a href="#%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%B2%D0%BE%D0%B5-%D1%81%D0%BB%D0%BE%D0%B2%D0%BE-virtual">Ключевое слово virtual</a></li>
		<li><a href="#%D0%BA%D0%BE%D0%B4%D0%BE%D0%B2%D1%8B%D0%B5-%D1%82%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D1%8B-%D0%B8-%D1%8E%D0%BD%D0%B8%D0%BA%D0%BE%D0%B4">Кодовые таблицы и юникод</a></li>
		<li><a href="#%D0%BA%D0%BE%D0%BC%D0%BF%D0%BE%D0%B7%D0%B8%D1%86%D0%B8%D1%8F">Композиция</a></li>
		<li><a href="#%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D0%B0%D0%BD%D1%82%D0%BD%D0%BE%D1%81%D1%82%D1%8C">Константность</a></li>
		<li><a href="#%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D0%BE%D1%80">Конструктор</a></li>
		<li><a href="#%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D0%BE%D1%80-%D0%BA%D0%BE%D0%BF%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F">Конструктор копирования</a></li>
		<li><a href="#%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%B9%D0%BD%D0%B5%D1%80%D1%8B-%28%D0%B2-%D1%81%D1%82%D0%B0%D0%BD%D0%B4%D0%B0%D1%80%D1%82%D0%BD%D0%BE%D0%B9-%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B5%29">Контейнеры (в стандартной библиотеке)</a></li>
		<li><a href="#%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%B9%D0%BD%D0%B5%D1%80%D1%8B-%28%D0%BE%D1%81%D0%BD%D0%BE%D0%BD%D1%8B%D0%B5-%D0%BF%D0%BE%D0%BD%D1%8F%D1%82%D0%B8%D1%8F%29">Контейнеры (осноные понятия)</a></li>
		<li><a href="#%D0%BA%D0%BE%D0%BF%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%BE%D0%B2">Копирование объектов</a></li>
		<li><a href="#%D0%BB%D0%BE%D0%B3%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5">Логирование</a></li>
		<li><a href="#%D0%BC%D0%B0%D0%BA%D1%80%D0%BE%D1%81%D1%8B">Макросы</a></li>
		<li><a href="#%D0%BC%D0%B0%D0%BD%D0%B8%D0%BF%D1%83%D0%BB%D1%8F%D1%82%D0%BE%D1%80%D1%8B-%D0%B8-%D0%B8%D1%85-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5">Манипуляторы и их использование</a></li>
		<li><a href="#%D0%BC%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%B5-%D1%81%D0%BB%D0%BE%D0%B2%D0%BE">Машинное слово</a></li>
		<li><a href="#%D0%BC%D0%B5%D1%82%D0%BE%D0%B4">Метод</a></li>
		<li><a href="#%D0%BC%D0%BE%D0%B4%D0%B5%D0%BB%D1%8C-%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D0%B8">Модель памяти</a></li>
		<li><a href="#%D0%BD%D0%BE%D0%BB%D1%8C">Ноль</a></li>
		<li><a href="#%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D1%8C-%D0%B2%D0%B8%D0%B4%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8-%28scope%29">Область видимости (scope)</a></li>
		<li><a href="#%D0%BE%D0%B1%D0%BE%D0%B1%D1%89%D0%B5%D0%BD%D0%BD%D0%BE%D0%B5-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5">Обобщенное программирование</a></li>
		<li><a href="#%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0-%D0%B2%D1%85%D0%BE%D0%B4%D0%BD%D1%8B%D1%85-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85">Обработка входных данных</a></li>
		<li><a href="#%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0-%D0%BE%D1%88%D0%B8%D0%B1%D0%BE%D0%BA-%28%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B%29">Обработка ошибок (методы)</a></li>
		<li><a href="#%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82">Объект</a></li>
		<li><a href="#%D0%BE%D0%B1%D1%8A%D1%8F%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5">Объявление</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80">Оператор</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80-%D0%BF%D1%80%D0%B8%D1%81%D0%B2%D0%B0%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F">Оператор присваивания</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B---%D0%BF%D1%80%D0%B8%D0%BE%D1%80%D0%B8%D1%82%D0%B5%D1%82%D1%8B">Операторы - приоритеты</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%D0%B0%D1%80%D0%B8%D1%84%D0%BC%D0%B5%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5">Операторы арифметические</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%D0%B1%D0%B8%D1%82%D0%BE%D0%B2%D1%8B%D0%B5">Операторы битовые</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4%D0%B0-%D0%B8-%D0%B2%D0%B2%D0%BE%D0%B4%D0%B0">Операторы вывода и ввода</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%B0">Операторы доступа</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5">Операторы логические</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%D1%81%D1%80%D0%B0%D0%B2%D0%BD%D0%B5%D0%BD%D0%B8%D1%8F">Операторы сравнения</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%D1%83%D0%BD%D0%B0%D1%80%D0%BD%D1%8B%D0%B5---%D0%BF%D1%80%D0%B5%D1%84%D0%B8%D0%BA%D1%81%D0%BD%D0%B0%D1%8F-%D0%B8-%D0%BF%D0%BE%D1%81%D1%82%D1%84%D0%B8%D0%BA%D1%81%D0%BD%D0%B0%D1%8F-%D1%84%D0%BE%D1%80%D0%BC%D1%8B">Операторы унарные - префиксная и постфиксная формы</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%8B-%D0%BF%D0%B5%D1%80%D0%B5%D0%B3%D1%80%D1%83%D0%B7%D0%BA%D0%B0">Операторы, перегрузка</a></li>
		<li><a href="#%D0%BE%D0%BF%D1%80%D0%B5%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5">Определение</a></li>
		<li><a href="#%D0%BE%D1%82%D0%BB%D0%B0%D0%B4%D1%87%D0%B8%D0%BA">Отладчик</a></li>
		<li><a href="#%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C-%D0%B4%D0%B8%D0%BD%D0%B0%D0%BC%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F">Память динамическая</a></li>
		<li><a href="#%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C-%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F">Память статическая</a></li>
		<li><a href="#%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C-%D1%81%D1%82%D0%B5%D0%BA%D0%BE%D0%B2%D0%B0%D1%8F">Память стековая</a></li>
		<li><a href="#%D0%BF%D0%B0%D0%BC%D1%8F%D1%82%D1%8C-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%D0%B2-%D1%81%D1%82%D0%B0%D0%BD%D0%B4%D0%B0%D1%80%D1%82%D0%BD%D0%BE%D0%B9-%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B5">Память, работа в стандартной библиотеке</a></li>
		<li><a href="#%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%B0%D1%8F">Переменная</a></li>
		<li><a href="#%D0%BF%D0%BE%D0%BB%D0%B5">Поле</a></li>
		<li><a href="#%D0%BF%D0%BE%D1%80%D1%8F%D0%B4%D0%BE%D0%BA-%D0%B1%D0%B0%D0%B9%D1%82%D0%BE%D0%B2">Порядок байтов</a></li>
		<li><a href="#%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B8-%D1%81%D1%82%D0%B0%D0%BD%D0%B4%D0%B0%D1%80%D1%82%D0%BD%D1%8B%D0%B5">Потоки стандартные</a></li>
		<li><a href="#%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B8-%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%BE%D0%B2%D1%8B%D0%B5">Потоки строковые</a></li>
		<li><a href="#%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B8-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%D1%8B%D0%B5">Потоки файловые</a></li>
		<li><a href="#%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%B0%D0%BA%D1%82%D1%83">Программирование по контракту</a></li>
		<li><a href="#%D0%BF%D1%80%D0%BE%D0%B8%D0%B7%D0%B2%D0%BE%D0%B4%D1%8F%D1%89%D0%B0%D1%8F-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8F">Производящая функция</a></li>
		<li><a href="#%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%80%D0%B0%D0%BD%D1%81%D1%82%D0%B2%D0%B0-%D0%B8%D0%BC%D0%B5%D0%BD-%28namespace%29">Пространства имен (namespace)</a></li>
		<li><a href="#%D0%BF%D1%81%D0%B5%D0%B2%D0%B4%D0%BE%D0%BD%D0%B8%D0%BC-%D1%82%D0%B8%D0%BF%D0%B0">Псевдоним типа</a></li>
		<li><a href="#%D0%BF%D1%81%D0%B5%D0%B2%D0%B4%D0%BE%D1%81%D0%BB%D1%83%D1%87%D0%B0%D0%B9%D0%BD%D1%8B%D0%B5-%D1%87%D0%B8%D1%81%D0%BB%D0%B0">Псевдослучайные числа</a></li>
		<li><a href="#%D1%80%D0%B0%D0%B7%D0%B4%D0%B5%D0%BB%D1%8C%D0%BD%D0%B0%D1%8F-%D0%BA%D0%BE%D0%BC%D0%BF%D0%B8%D0%BB%D1%8F%D1%86%D0%B8%D1%8F">Раздельная компиляция</a></li>
		<li><a href="#%D1%80%D0%B5%D0%BA%D1%83%D1%80%D1%81%D0%B8%D1%8F">Рекурсия</a></li>
		<li><a href="#%D1%81%2B%2B-%28%D0%BE%D0%B1%D1%89%D0%B8%D0%B5-%D1%81%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F-%D0%BE%D1%82%D0%BD%D0%BE%D1%88%D0%B5%D0%BD%D0%B8%D0%B5-%D1%81-%D1%81%29">С++ (общие сведения, отношение с с)</a></li>
		<li><a href="#%D1%81%D0%B2%D1%8F%D0%B7%D1%8B%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5">Связывание</a></li>
		<li><a href="#%D1%81%D0%BF%D0%B5%D1%86%D0%B8%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F">Специализация</a></li>
		<li><a href="#%D1%81%D1%81%D1%8B%D0%BB%D0%BA%D0%B0">Ссылка</a></li>
		<li><a href="#%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D0%B0%D1%8F">Статическая переменная</a></li>
		<li><a href="#%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9-%D1%87%D0%BB%D0%B5%D0%BD-%28%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B0%29">Статический член (класса)</a></li>
		<li><a href="#%D1%81%D1%82%D0%B5%D0%BA-%D0%B2%D1%8B%D0%B7%D0%BE%D0%B2%D0%BE%D0%B2">Стек вызовов</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D0%B0%D0%B6%D0%B8-%D0%B2%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D1%8F">Стражи включения</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8-%28%D1%81-%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8%29-%D0%B8-%D0%BB%D0%B8%D1%82%D0%B5%D1%80%D0%B0%D0%BB%D1%8B-%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0">Строки (с-строки) и литералы, обработка</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8-std%3A%3Astring-%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0">Строки std::string, обработка</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0">Структура</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85">Структура данных</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%C2%AB%D0%B3%D1%80%D0%B0%D1%84%C2%BB">Структура данных «граф»</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%C2%AB%D0%B4%D0%B5%D1%80%D0%B5%D0%B2%D0%BE%C2%BB">Структура данных «дерево»</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%C2%AB%D0%BA%D0%BE%D1%80%D1%82%D0%B5%D0%B6%C2%BB">Структура данных «кортеж»</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%C2%AB%D0%BC%D0%B0%D1%81%D1%81%D0%B8%D0%B2%C2%BB">Структура данных «массив»</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%C2%AB%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA-%D0%B4%D0%B2%D1%83%D1%81%D0%B2%D1%8F%D0%B7%D0%BD%D1%8B%D0%B9%C2%BB">Структура данных «список двусвязный»</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%C2%AB%D1%81%D0%BF%D0%B8%D1%81%D0%BE%D0%BA-%D0%BE%D0%B4%D0%BD%D0%BE%D1%81%D0%B2%D1%8F%D0%B7%D0%BD%D1%8B%D0%B9%C2%BB">Структура данных «список односвязный»</a></li>
		<li><a href="#%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%C2%AB%D1%85%D0%B5%D1%88-%D1%82%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D0%B0%C2%BB">Структура данных «хеш-таблица»</a></li>
		<li><a href="#%D1%82%D0%B5%D0%BA%D1%81%D1%82-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B-%D0%BA%D0%BE%D0%BC%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%80%D0%B8%D0%B8">Текст программы, комментарии</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-pod">Тип pod</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-void">Тип void</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-%D0%B2%D0%B5%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9">Тип вещественный</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-%D0%B2%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9">Тип встроенный</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85">Тип данных</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85---%D0%BF%D1%80%D0%B8%D0%BD%D1%86%D0%B8%D0%BF%D1%8B-%D0%B2%D1%8B%D0%B1%D0%BE%D1%80%D0%B0">Тип данных - принципы выбора</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-%D0%BA%D0%BE%D0%BF%D0%B8%D1%80%D1%83%D0%B5%D0%BC%D1%8B%D0%B9">Тип копируемый</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-%D0%BB%D0%BE%D0%B3%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9">Тип логический</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-%D0%BF%D0%B5%D1%80%D0%B5%D1%87%D0%B8%D1%81%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5">Тип перечисление</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-%D1%81%D0%B8%D0%BC%D0%B2%D0%BE%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9">Тип символьный</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-%D1%81%D1%82%D0%B0%D0%BD%D0%B4%D0%B0%D1%80%D1%82%D0%BD%D0%BE%D0%B9-%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B8">Тип стандартной библиотеки</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF-%D1%86%D0%B5%D0%BB%D1%8B%D0%B9">Тип целый</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF%D0%BE%D0%B2-%D0%BF%D1%80%D0%B5%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BD%D0%B5%D1%8F%D0%B2%D0%BD%D1%8B%D0%B5">Типов преобразования неявные</a></li>
		<li><a href="#%D1%82%D0%B8%D0%BF%D0%BE%D0%B2-%D0%BF%D1%80%D0%B5%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D1%8F%D0%B2%D0%BD%D1%8B%D0%B5">Типов преобразования явные</a></li>
		<li><a href="#%D1%83%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D1%8C">Указатель</a></li>
		<li><a href="#%D1%83%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D1%8C-%D0%BD%D0%B0-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8E">Указатель на функцию</a></li>
		<li><a href="#%D1%83%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%BE%D0%BC">Управление доступом</a></li>
		<li><a href="#%D1%84%D1%83%D0%BD%D0%BA%D1%82%D0%BE%D1%80-%28%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9-%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%29">Функтор (функциональный объект)</a></li>
		<li><a href="#%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8F">Функция</a></li>
		<li><a href="#%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8F---%D0%BF%D0%B5%D1%80%D0%B5%D0%B3%D1%80%D1%83%D0%B7%D0%BA%D0%B0">Функция - перегрузка</a></li>
		<li><a href="#%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8F---%D0%BF%D0%B5%D1%80%D0%B5%D0%B4%D0%B0%D1%87%D0%B0-%D0%BF%D0%B0%D1%80%D0%B0%D0%BC%D0%B5%D1%82%D1%80%D0%BE%D0%B2-%D0%B2%D0%BE%D0%B7%D0%B2%D1%80%D0%B0%D1%82-%D0%B7%D0%BD%D0%B0%D1%87%D0%B5%D0%BD%D0%B8%D1%8F">Функция - передача параметров, возврат значения</a></li>
		<li><a href="#%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8F-main">Функция main</a></li>
		<li><a href="#%D1%88%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD---%D0%BF%D0%B0%D1%80%D0%B0%D0%BC%D0%B5%D1%82%D1%80%D1%8B">Шаблон - параметры</a></li>
		<li><a href="#%D1%88%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD%D0%BD%D0%B0%D1%8F-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D1%8F">Шаблонная функция</a></li>
		<li><a href="#%D1%88%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD%D0%BD%D1%8B%D0%B9-%D1%82%D0%B8%D0%BF">Шаблонный тип</a></li>
		<li><a href="#abi">ABI</a></li>
		<li><a href="#pimpl">PIMPL</a></li>
		<li><a href="#raii">RAII</a></li>
		<li><a href="#ref-qualifiers-for-%2Athis">Ref-qualifiers for *this</a></li>
		<li><a href="#singleton">Singleton</a></li>
		<li><a href="#std%3A%3Abitset">std::bitset</a></li>
		<li><a href="#std%3A%3Aforward">std::forward</a></li>
		<li><a href="#std%3A%3Amove">std::move</a></li>
		<li><a href="#std%3A%3Ashared_ptr">std::shared_ptr</a></li>
		<li><a href="#std%3A%3Aunique_ptr">std::unique_ptr</a></li>
		<li><a href="#std%3A%3Aweak_ptr">std::weak_ptr</a></li>
		<li><a href="#%D0%B0%D0%B1%D1%81%D1%82%D1%80%D0%B0%D0%BA%D1%82%D0%BD%D1%8B%D0%B9-%D0%BA%D0%BB%D0%B0%D1%81%D1%81">Абстрактный класс</a></li>
		<li><a href="#%D0%B2%D0%B8%D1%80%D1%82%D1%83%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9-%D0%B2%D1%8B%D0%B7%D0%BE%D0%B2-%D0%B2%D0%B8%D1%80%D1%82%D1%83%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%B8">Виртуальный вызов, виртуальные функции</a></li>
		<li><a href="#%D0%B4%D0%B8%D0%BD%D0%B0%D0%BC%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9-%D0%BF%D0%BE%D0%BB%D0%B8%D0%BC%D0%BE%D1%80%D1%84%D0%B8%D0%B7%D0%BC">Динамический полиморфизм</a></li>
		<li><a href="#%D0%B7%D0%B0%D0%B2%D0%B8%D1%81%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8-%D0%BF%D0%B0%D0%BA%D0%B5%D1%82%D0%BD%D1%8B%D0%B5-%D0%BC%D0%B5%D0%BD%D0%B5%D0%B4%D0%B6%D0%B5%D1%80%D1%8B">Зависимости, пакетные менеджеры</a></li>
		<li><a href="#%D0%B7%D0%B0%D0%BC%D0%B5%D1%80%D1%8B-%D0%B2%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%B8">Замеры времени</a></li>
		<li><a href="#%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%B2%D0%BE%D0%B5-%D1%81%D0%BB%D0%BE%D0%B2%D0%BE-final">Ключевое слово final</a></li>
		<li><a href="#%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%B2%D0%BE%D0%B5-%D1%81%D0%BB%D0%BE%D0%B2%D0%BE-mutable">Ключевое слово mutable</a></li>
		<li><a href="#%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D0%BE%D1%80-%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D1%89%D0%B0%D1%8E%D1%89%D0%B8%D0%B9">Конструктор перемещающий</a></li>
		<li><a href="#%D0%BB%D1%8F%D0%BC%D0%B1%D0%B4%D1%8B-generic">Лямбды, generic</a></li>
		<li><a href="#%D0%BB%D1%8F%D0%BC%D0%B1%D0%B4%D1%8B-%D0%B7%D0%B0%D1%85%D0%B2%D0%B0%D1%82">Лямбды, захват</a></li>
		<li><a href="#%D0%BB%D1%8F%D0%BC%D0%B1%D0%B4%D1%8B-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5">Лямбды, использование</a></li>
		<li><a href="#%D0%BB%D1%8F%D0%BC%D0%B1%D0%B4%D1%8B-%D0%BE%D0%B1%D1%89%D0%B8%D0%B5-%D1%81%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F">Лямбды, общие сведения</a></li>
		<li><a href="#%D0%BB%D1%8F%D0%BC%D0%B1%D0%B4%D1%8B-%D1%85%D1%80%D0%B0%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5">Лямбды, хранение</a></li>
		<li><a href="#%D0%BC%D0%BD%D0%BE%D0%B6%D0%B5%D1%81%D1%82%D0%B2%D0%B5%D0%BD%D0%BD%D0%BE%D0%B5-%D0%BD%D0%B0%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5">Множественное наследование</a></li>
		<li><a href="#%D0%BD%D0%B0%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%28%D0%B2-%D1%8F%D0%B7%D1%8B%D0%BA%D0%B5%29">Наследование (в языке)</a></li>
		<li><a href="#%D0%BD%D0%B0%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%28%D0%BE%D0%B3%D1%80%D0%B0%D0%BD%D0%B8%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%B0%29">Наследование (ограничение доступа)</a></li>
		<li><a href="#%D0%BE%D0%BE%D0%BF-%D0%B1%D0%B0%D0%B7%D0%BE%D0%B2%D1%8B%D0%B5-%D0%BF%D1%80%D0%B8%D0%BD%D1%86%D0%B8%D0%BF%D1%8B">ООП, базовые принципы</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80-%22%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF-%D0%BA-%D1%87%D0%BB%D0%B5%D0%BD%D1%83-%D1%87%D0%B5%D1%80%D0%B5%D0%B7-%D1%83%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%22">Оператор "доступ к члену через указатель"</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80-%22%D0%B7%D0%B0%D0%BF%D1%8F%D1%82%D0%B0%D1%8F%22">Оператор "запятая"</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80-%22%D0%BF%D1%80%D0%B8%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BA-%D1%82%D0%B8%D0%BF%D1%83%22">Оператор "приведение к типу"</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80-%22%D1%80%D0%B0%D0%B7%D1%8B%D0%BC%D0%B5%D0%BD%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%22">Оператор "разыменование"</a></li>
		<li><a href="#%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80-%D0%BF%D1%80%D0%B8%D1%81%D0%B2%D0%B0%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D1%89%D0%B0%D1%8E%D1%89%D0%B8%D0%B9">Оператор присваивания перемещающий</a></li>
		<li><a href="#%D0%BF%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D1%89%D0%B5%D0%BD%D0%B8%D0%B5">Перемещение</a></li>
		<li><a href="#%D0%BF%D0%BE%D0%B4%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BE%D1%87%D0%BD%D1%8B%D0%B9-%D0%BA%D1%80%D0%B8%D1%82%D0%B5%D1%80%D0%B8%D0%B9">Подстановочный критерий</a></li>
		<li><a href="#%D0%B2%D1%8B%D1%80%D0%B0%D0%B2%D0%BD%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5">Выравнивание</a></li>
		<li><a href="#%D0%BF%D1%80%D0%B5%D0%B4%D1%83%D0%BF%D1%80%D0%B5%D0%B6%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F">Предупреждения</a></li>
		<li><a href="#%D0%BF%D1%80%D0%B5%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE%D0%B2%D1%8B%D1%88%D0%B0%D1%8E%D1%89%D0%B5%D0%B5">Преобразование повышающее</a></li>
		<li><a href="#%D0%BF%D1%80%D0%B5%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D0%BE%D0%BD%D0%B8%D0%B6%D0%B0%D1%8E%D1%89%D0%B5%D0%B5">Преобразование понижающее</a></li>
		<li><a href="#%D0%BF%D1%80%D0%B8%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D1%82%D0%B8%D0%BF%D0%B0-bit_cast-">Приведение типа bit_cast<></a></li>
		<li><a href="#%D0%BF%D1%80%D0%B8%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D1%82%D0%B8%D0%BF%D0%B0-const_cast-">Приведение типа const_cast<></a></li>
		<li><a href="#%D0%BF%D1%80%D0%B8%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D1%82%D0%B8%D0%BF%D0%B0-dynamic_cast-">Приведение типа dynamic_cast<></a></li>
		<li><a href="#%D0%BF%D1%80%D0%B8%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D1%82%D0%B8%D0%BF%D0%B0-reinterpret_cast-">Приведение типа reinterpret_cast<></a></li>
		<li><a href="#%D0%BF%D1%80%D0%B8%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D1%82%D0%B8%D0%BF%D0%B0-static_cast-">Приведение типа static_cast<></a></li>
		<li><a href="#%D0%BF%D1%80%D0%BE%D0%B8%D0%B7%D0%B2%D0%BE%D0%B4%D0%BD%D1%8B%D0%B5-%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D1%8B-%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B8-%D1%83%D0%BD%D0%B8%D1%87%D1%82%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5">Производные объекты, конструирование и уничтожение</a></li>
		<li><a href="#%D0%BF%D1%80%D1%8F%D0%BC%D0%B0%D1%8F-%D0%BF%D0%B5%D1%80%D0%B5%D0%B4%D0%B0%D1%87%D0%B0">Прямая передача</a></li>
		<li><a href="#%D1%81%D1%81%D1%8B%D0%BB%D0%BA%D0%B0-%28%D0%BF%D1%80%D0%B0%D0%B2%D0%B0%D1%8F%29">Ссылка (правая)</a></li>
		<li><a href="#%D1%88%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD-%D1%81%D0%BF%D0%B5%D1%86%D0%B8%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F">Шаблон, специализация</a></li>
	</ol>
</details>

<hr style="width:25%;text-align:left;margin-left:0">

## l-value и r-value

l-value - это выражение, которое имеет идентификатор и адрес в памяти, куда можно присвоить значение.

r-value - это выражение, которое не имеет адреса в памяти и часто используется как значение.

### Примеры
```C++
int x = 5; // x - l-value, 5 - r-value
```

<hr style="width:25%;text-align:left;margin-left:0">

## nullptr, NULL, 0

nullptr - введен в стандарте C++11 и представляет собой безопасную замену для NULL и 0 в указателях. nullptr имеет тип std::nullptr_t и может быть присвоен любому указателю.

0 - также используется для представления нулевого указателя.

NULL - это макрос, обычно определенный как #define NULL 0, который используется для представления нулевого указателя (наследство из C -> не используем).

В C++11 и более поздних стандартах рекомендуется использовать nullptr вместо NULL и 0, так как nullptr имеет явный тип и предотвращает некоторые ошибки, связанные с неправильным использованием нулевых указателей.

### Примеры
```C++
int* ptr1 = nullptr;
int* ptr2 = NULL;
int* ptr3 = 0;
```

<hr style="width:25%;text-align:left;margin-left:0">

## Алгоритм бинарного поиска

Бинарный поиск — это эффективный алгоритм поиска, который используется для нахождения позиции заданного элемента в отсортированном массиве. Принцип работы бинарного поиска заключается в последовательном делении массива на две части и сравнении искомого значения со значением элемента в середине массива.

Преимущества бинарного поиска:
* Высокая эффективность: Время выполнения бинарного поиска — O(log n), где n — количество элементов в массиве.
* Простота реализации: Легко реализовать и отладить.

Ограничения:
* Требует отсортированного массива.
* Подходит только для последовательного доступа: Не подходит для структур данных с произвольным доступом, таких как связные списки.

Сложность по времени: O(log n)

Сложность по памяти: O(1)

### Примеры
```C++
std::vector<int> vec = { 1, 3, 5, 7, 9, 11, 13 }; // Вектор уже отсортирован
int target = 7; // искомое значение
std::binary_search(vec.begin(), vec.end(), target) // true - найден, false - нет
```

<hr style="width:25%;text-align:left;margin-left:0">

## Алгоритм сортировки, основные характеристики

Алгоритмы сортировки позволяют упорядочить данные для эффективного доступа и обработки. Основные характеристики алгоритмов сортировки включают сложность по времени и памяти, стабильность и адаптивность.

### Примеры
Пузырьковая сортировка (Bubble Sort)
* Сложность по времени: O(n^2) в худшем и среднем случае, O(n) в лучшем случае (если массив уже отсортирован).
* Сложность по памяти: O(1), так как не требует дополнительной памяти.
* Стабильность: Стабильный (не меняет порядок равных элементов).
* Адаптивность: Адаптивен (способность алгоритма работать быстрее на частично отсортированных данных).

<hr style="width:25%;text-align:left;margin-left:0">

##  Алгоритм хеширования

Это функция, преобразующая входные данные произвольной длины в строку фиксированной длины, часто называемую хеш-кодом. Полученный хеш обычно имеет меньший размер, чем исходные данные.

Хеширование используется во многих областях информационной безопасности, включая проверку целостности данных и аутентификацию. Алгоритмы хеширования позволяют распознавать изменённые данные, они применяются в базах данных для более эффективного доступа к данным, в цифровых подписях, блокчейнах и хранении паролей.

Свойства:
* Детерминированность: одни и те же входные данные всегда приводят к тому же хеш-коду.
* Быстрое вычисление: хеш можно вычислить относительно быстро для любого объема входных данных.
* Эффект лавины: небольшое изменение входных данных вызывает существенное изменение результата хеширования.
* Необратимость: невозможно восстановить исходные данные по их хеш-коду.
* Стойкость к коллизиям: сложность нахождения второго входного значения, которое имеет такой же хэш, как и данное входное значение (слабая/сильная).

### Примеры
```C++
std::unordered_map<std::string, int> umap;

// Вставка элементов в unordered_map
umap["apple"] = 2;
umap["banana"] = 4;
umap["orange"] = 3;

// Альтернативный способ вставки с использованием метода insert
umap.insert({ "pear", 5 });
```

<hr style="width:25%;text-align:left;margin-left:0">

##  Алгоритмы стандартной библиотеки

Стандартная библиотека - коллекция классов, функций, макросов и констант.

Находятся в <algorithm>.

Основные категории алгоритмов:
* Алгоритмы поиска и проверки.
* Алгоритмы сортировки и упорядочивания.
* Алгоритмы модификации.
* Алгоритмы копирования и перемещения.
* Алгоритмы генерации и удаления.
* Алгоритмы численных операций.

### Примеры
```C++
int x = 1;
int y = 2;
std::min(x, y); // 1
std::max(x, y); // 2

std::vector<int> vec = { 1, 2, 3, 4, 5 };
std::find(vec.begin(), vec.end(), 3); // поиск индекса эллемента '3'

std::binary_search(vec.begin(), vec.end(), 3); // true - '3' найдено, false - '3' не найдено

std::vector<int> vec = {5, 3, 1, 4, 2};
std::sort(vec.begin(), vec.end()); // vec = { 1, 2, 3, 4, 5 }

std::reverse(vec.begin(), vec.end()); // vec = { 5, 4, 3, 2, 1 }

std::replace(vec.begin(), vec.end(), 1, 9); // vec = { 5, 4, 3, 2, 9 }

std::vector<int> vec_copy(5);
std::copy(vec.begin(), vec.end(), vec_copy.begin()); // vec_copy = { 5, 4, 3, 2, 9 }

std::vector<int> vec_move(5);
std::move(vec_copy.begin(), vec_copy.end(), vec_move.begin()); // vec_move = { 5, 4, 3, 2, 9 } vec_copy = { }
```

<hr style="width:25%;text-align:left;margin-left:0">

##  Алфавит и идентификатор

Алфавит C++ состоит из следующих символов:

1. Буквы:
* Заглавные латинские буквы: A-Z.
* Строчные латинские буквы: a-z.
* Цифры: 0-9.

2. Специальные символы:
* Символы пунктуации: +, -, *, /, %, =, &, |, !, ^, ~, <, >, ?, :, ;, ,, ., @, #, $, _
* Скобки и операторы: (), {}, [], ::, ->, .

3. Пробелы и управляющие символы:
* Пробел, табуляция и другие символы управления, такие как \n (новая строка), \t (табуляция) и т.д.
* Идентификаторы — это имена, которые программист присваивает переменным, функциям, классам, объектам и другим элементам программы. Правила именования идентификаторов в C++:

Начало идентификатора:
* Должен начинаться с буквы (заглавной или строчной) или символа подчеркивания _.
* Не может начинаться с цифры.

Содержимое идентификатора:
* Может содержать буквы, цифры и символы подчеркивания.
* Пробелы и специальные символы (кроме _) не допускаются.

Регистр имеет значение:
* C++ различает идентификаторы, записанные в разном регистре. Например, Variable и variable считаются разными идентификаторами.

Ключевые слова:
* Идентификаторы не могут совпадать с ключевыми словами языка C++ (например, int, class, return и т.д.).

Стиль именования:
* Стиль именования может следовать соглашениям, принятым в проекте или команде. Например, CamelCase, snake_case и т.д.

### Примеры
```C++
int myVariable;       // допустимый идентификатор
int _my_variable;     // допустимый идентификатор
int variable2;        // допустимый идентификатор
int Variable;         // допустимый идентификатор, отличается от "variable"
int 2variable;        // недопустимый идентификатор, начинается с цифры
int my-variable;      // недопустимый идентификатор, содержит дефис
int int;              // недопустимый идентификатор, совпадает с ключевым словом
```

<hr style="width:25%;text-align:left;margin-left:0">

<p align="right">(<a href="#readme-top">Вернуться в начало</a>)</p>
