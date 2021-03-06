# Дерево с чекбоксами

[importance 5]

Вы получили проект, в котором есть дерево с чекбоксами.

К сожалению, оно "кривое" -- некрасивое, плохо закодированное и с ошибками. Ваша задача -- сделать "как надо".

Образец:

[iframe src="source" height=400 link edit border=1]

Особенности работы:
<ul>
<li>При изначальном рисовании все элементы закрыты и не отмечены.</li>
<li>Установка отметки в чекбоксе раскрывает узел и отмечает все элементы под ним.</li>
<li>Снятие отметки из чекбокса -- снимает отметки из всех элементов под ним.</li>
</ul>

Требования к реализации:
<ul>
<li>Все данные для дерева (регионы) нужно хранить в JS. Как именно -- определяете вы сами. Можно в одном объекте, можно -- ещё как-то.</li>
<li>Программист, который делал этот код, сейчас недоступен. Ваша задача -- восстановить данные регионов из дерева примера.</li>
<li>Можно считать, что название региона всегда занимает только 1 строку.</li>
<li>Дерево должно легко работать с 1000 узлов (в примере их около 450).</li>
<li>Используйте минимум DOM-элементов.</li>
</ul>

Исходный документ содержит "образец" дерева.

[edit task src="source"/]

P.S. При получении данных из дерева-образца вам поможет `JSON.stringify(объект)`. Он превратит объект в строку, которую можно положить в файл.
