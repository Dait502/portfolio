# portfolio


|№| Название проекта | Суть и результат | 	Навыки и инструменты |
|----------|----------|----------|----------|
|1   |Анализ бизнес-показателей на основе данных по продажам | Cell 3   | 1   |
 
| 2    | Создание дашборда по основным метрикам e-commerce магазина   | Cell 6   |2    | 
| 3    | Синтетическое тестирование  | Cell 9   |3    |

<table>
    <tr>
        <th>Влад</th>
        <th>Даун 2</th>
    </tr>
    <tr>
        <td>Анализ бизнес-показателей на 
          основе данных по продажам</td>
        <td>Ячейка 2.1</td>
    </tr>
    <tr>
        <td>Ячейка 1.2</td>
        <td>Ячейка 2.2</td>
    </tr>
</table>

No, this is not possible with GitHub-Flavored Markdown. As the spec explains (emphasis added):

The remainder of the table’s rows may vary in the number of cells. If there are a number of cells fewer than the number of cells in the header row, empty cells are inserted. If there are greater, the excess is ignored:

Of course, you can always fall back to raw HTML.

<table>
    <thead>
        <tr>
            <th>Layer 1</th>
            <th>Layer 2</th>
            <th>Layer 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>L1 Name</td>
            <td rowspan=2>L2 Name A</td>
            <td>L3 Name A</td>
        </tr>
        <tr>
            <td>L3 Name B</td>
        </tr>
        <tr>
            <td rowspan=2>L2 Name B</td>
            <td>L3 Name C</td>
        </tr>
        <tr>
            <td>L3 Name D</td>
        </tr>
    </tbody>
</table>
