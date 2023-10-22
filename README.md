# `Класс DoublyLinkedList`

[метод](https://github.com/coldjulicc/algorithm/blob/main/algosi.cpp#L192) работает за: $$O(1)$$ потому что - в методе нет ни циклов, ни рекрсий, все команды в методе выполняются за константу, а значит и весь метод будет работать за O(1)
___

# `Класс DynamicArray`
[метод](https://github.com/coldjulicc/algorithm/blob/main/algosi.cpp#L311) работает за: $$O(1)$$, потому что как и в прыдыдушем методе, все команды выполняются за констранту, а это значит что сложность не зависит от размера подоваемых данных (в нашем случае n)
___
# `Функция evaluateExpression`
[функция](https://github.com/coldjulicc/algorithm/blob/main/algosi.cpp#L371) работает за: $$O(n^2 + n)$$ потому что в функции два вложных цикла. А именно внешний который зависит от аргумента функции(string expression). И внутрений, который запуститься если символ сторки expression окажется цифрой. Также на сложность влияет последний цикл while. Который зависит от длины стека operators, а длина стека operators зависит от длины строки expression, то есть от n.


![Пример картинки](https://github.com/coldjulicc/algorithm/v1.JPG)
