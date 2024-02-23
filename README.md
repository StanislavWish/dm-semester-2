# dm-semester-2

## Определения

1. [Инцидентность вершин и ребер](#инцидентность-вершин-и-ребер)
2. [Смежность вершин и ребер](#смежность-вершин-и-ребер)
3. [Изолированная вершина](#изолированная-вершина)
4. [Висячая вершина](#висячая-вершина)
5. [Мультиграф](#мультиграф)
6. [Псевдограф](#псевдограф)
7. [Матрица смежности](#матрица-смежности)
8. [Матрица инцедентности](#матрица-инцедентности)
9. [Кратные дуги](#кратные-дуги)
10. [Симметричные дуги](#симметричные-дуги)
11. [Направленный граф](#направленный-граф)
12. [Лемма о рукопожатиях](#лемма-о-рукопожатиях)
13. [Подграф и надграф](#подграф-и-надграф)
14. [Частичный граф](#частичный-граф)
15. [Объединение и пересечение графов]()
16. [Подразбиение ребра]()
17. [Отождествление вершин]()
18. [Стягивание ребра]()
19. [Регулярный граф, степень регулярности]()
20. [Хроматическое число]()
21. [Клика, кликовое число]()
22. [Изоморфизм графов]()
23. [Путь и замкнутый путь]()
24. [Цепь и цикл]()
25. [Простая цепь и простой цикл]()
26. [Связность (достижимость) вершин, компонента связности]()
27. [Сильная связность вершин, компонента сильной связности]()

## Инцидентность вершин и ребер

> *x* — ребро с концами *u* и *v*, *{u, v}*, тогда *x* инцидентно *u* и *v*, *u* и *v* инцидентны *x*

## Смежность вершин и ребер

> вершины *u* и *v* называются смежными, если являются концами
одного ребра

> ребра *x* и *y* называются смежными, если имеют общую вершину

## Изолированная вершина

> Изолированная вершина — вершина
без петель также не являющаяся концом ни одного из ребер

## Висячая вершина

> Висячая вершина — вершина, в которую вдет только одно ребро, которое в свою очередь также называется висячим

## Мультиграф

> Мультиграф — граф с
параллельными ребрами

## Псевдограф

Псевдограф — граф, который может содержать:

* петли
* и/или параллельные ребра

## Матрица смежности

Матрица смежности — матрица A [V x V] , в которой в ячейке a_ij записано

* (неориентир.): число ребер, соединяющих вершины V_i и V_j.

* (ориентир.): a_ij = 1, если из V_i в V_j идет дуга, иначе 0

## Матрица инцедентности

> Матрица инцидентности (для **неориентированного** графа) — матрица A размера |V|x|E|, для которой a_ij = 1, если вершина v_i инцидентна ребру e_j, иначе a_ij = 0

> Матрица инцидентности (для **ориентированного** графа) — матрица A размера |V|x|E|, для которой a_ij = 1, если вершина v_i начало дуги e_j, a_ij = -1, если вершина v_i конец дуги e_j, иначе a_ij = 0

## Кратные дуги

> Несколько дуг с совпадающими начальными и конечными вершинами.

## Симметричные дуги

> Дуги вида (*u*, *v*) и (*v*, *u*) в некотором графе.

*u*, *v* ∊ V(G)

(*u*, *v*), (*v*, *u*) ∊ E(G)

## Направленный граф

> Направленный граф — граф без
симметричных ориентированных
ребер (дуг).

## Лемма о рукопожатиях

Неориентированный граф:

> Сумма степеней всех вершин графа — четное число, равное удвоенному числу ребер графа.

> Следствие: произвольный граф содержит четное число вершин нечетной
степени.

Ориентированный граф:

> Сумма входящих и исходящих степеней всех вершин графа — четное число, равно удвоенному числу дуг графа.

## Подграф и надграф

> Граф G'(V', E') является **подграфом** G(V, E), если V' ⊆ V, E' ⊆ E. Таким образом каждая вершина или ребро подграфа являются вершиной или ребром исходного графа.

> **Надграф** — граф, полученный путем добавления
новых ребер и/или вершин в исходный граф.

## Частичный граф

> Частичный граф — состоящий из множества вершин исходного графа и подмножества множества ребер.

*Каждый граф частичен сам себе.*