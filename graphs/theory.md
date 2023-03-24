# Графы

### Состав графа
Граф состоит из вершин, соединенных ребрами. Мы будем обозначать
буквой V количество вершин графа, а буквой E – количество ребер. Ребра
нумеруются числами 1, 2, . . . , V.
![Текст с описанием картинки](https://watery-orbit-cc0.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fa80c7de1-d263-42aa-837d-ad2a422091ee%2FUntitled.png?id=55c8ef7a-692c-4c78-bc19-86eb0e0b1a5f&table=block&spaceId=04a2f7a5-16f3-46e7-94be-8d6a3f7074ed&width=850&userId=&cache=v2)

### Цикл графа
Путь ведет из одной вершины в другую и проходит по ребрам графа.
Длиной пути называется количество ребер в нем. Например, путь
1 → 3 → 4 → 5 длины 3 из вершины 1 в вершину 5.

Циклом называется путь, в котором последняя вершина совпадает с первой. На рисунке изображен цикл 1 → 3 → 4 → 1.
![Текст с описанием картинки](https://watery-orbit-cc0.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Feecd61b7-d885-475d-80d9-bf28dd70507b%2FUntitled.png?id=ce02d559-ee0f-4f7e-b600-94e9aa0d14d1&table=block&spaceId=04a2f7a5-16f3-46e7-94be-8d6a3f7074ed&width=710&userId=&cache=v2)

### Связный граф
Граф называется связным, если между любыми двумя вершинами существует путь. Левый граф на рисунке связный, а правый – нет, потому что из вершины 4 нельзя попасть ни в какую другую.
![Текст с описанием картинки](https://watery-orbit-cc0.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fcec15853-62f4-4360-ad63-25cf4fdc7d88%2FUntitled.png?id=92a6758c-27d2-4da7-a04d-7f77fdc63958&table=block&spaceId=04a2f7a5-16f3-46e7-94be-8d6a3f7074ed&width=1180&userId=&cache=v2)

### Компоненты связности
Связные части графа называются его компонентами связности. Граф на
рисунке состоит из трех компонент связности: {1, 2, 3}, {4, 5, 6, 7} и {8}.
![Текст с описанием картинки](https://watery-orbit-cc0.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F0c043f5f-4df3-4e5d-acea-3105029d1243%2FUntitled.png?id=f7139350-ec4f-4ccd-9ee4-b27a6635ae28&table=block&spaceId=04a2f7a5-16f3-46e7-94be-8d6a3f7074ed&width=1330&userId=&cache=v2)

### Дерево - частный случай графа
Деревом называется связный граф без циклов.
![Текст с описанием картинки](https://watery-orbit-cc0.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F06324dd0-fcd1-4105-acac-8dcbfd10cbb9%2FUntitled.png?id=8b40e400-d68b-41be-bbb0-5bdee841cba1&table=block&spaceId=04a2f7a5-16f3-46e7-94be-8d6a3f7074ed&width=780&userId=&cache=v2)

### Ориентированный граф
В ориентированном графе по каждому ребру можно проходить только в
одном направлении. На рисунке показан пример ориентированного графа.
В нем имеется путь 3 → 1 → 2 → 5 из вершины 3 в вершину 5, но не существует пути из вершины 5 в вершину 3.

![Текст с описанием картинки](https://watery-orbit-cc0.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fee5f586b-47a3-47a9-8d3b-98f4b62c10f0%2FUntitled.png?id=e0380ecf-be84-4e2f-b98c-aa1d75b632f1&table=block&spaceId=04a2f7a5-16f3-46e7-94be-8d6a3f7074ed&width=810&userId=&cache=v2)
![Текст с описанием картинки](https://sun1-54.userapi.com/impf/NjG4KULsjWIvZLrN16TD-MWVl4DCSiQYKXFEvQ/0esndgrAwhk.jpg?size=566x252&quality=96&sign=8b3d8e0cc3f2fdd5522934e2fc34c754&type=album)

### Степень вершины графа
Две вершины называются соседними, или смежными, если они соединены ребром. Степенью вершины называется число соседних с ней вершин.
Граф называется полным, если степень каждой его вершины равна n − 1, т. е. в графе присутствуют все возможные ребра.
На рисунке показаны степени всех вершин графа. Так, степень вершины 2 равна 3, потому что ее соседями являются вершины 1, 4 и 5.
![Текст с описанием картинки](https://watery-orbit-cc0.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F57f52077-4acb-4c3d-9d83-9387ed9c3ce4%2FUntitled.png?id=91a05648-9bf1-4b99-8154-5cf07d9ac356&table=block&spaceId=04a2f7a5-16f3-46e7-94be-8d6a3f7074ed&width=820&userId=&cache=v2)

### Двудольный граф
Граф называется двудольным, если его вершины можно раскрасить в два цвета, так что цвета любых двух соседних вершин различны. Можно доказать, что граф является двудольным тогда и только тогда, когда в нем нет цикла с нечетным числом вершин.
![Текст с описанием картинки](https://watery-orbit-cc0.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fd3c8982d-a4a4-4ae7-b5ae-8c89e8dc9a0a%2FUntitled.png?id=34abc2fb-01e0-4aa8-9d85-7f9011bf7078&table=block&spaceId=04a2f7a5-16f3-46e7-94be-8d6a3f7074ed&width=900&userId=&cache=v2)

## Представление графа

**Списки смежности(adjacency list)**. В этом случае каждой вершине x сопоставляется
список смежности, включающий вершины, соединенные с x ребром. Списки смежности – самый популярный способ представления графов, они позволяют эффективно реализовать большинство алгоритмов.

Списки смежности удобно хранить в векторе векторов, который объявлен следующим образом:
```cpp
    vector<vector<int>> a(V + 1);
```
Например, граф на рисунке а можно сохранить так:
```cpp
    adj[1].push_back(2);
    adj[2].push_back(3);
    adj[2].push_back(4);
    adj[3].push_back(4);
    adj[4].push_back(1);
```
Неориентированные графы можно хранить аналогично, только каждое
ребро нужно учитывать в двух списках смежности (для обоих направлений).

Матрица смежности показывает, какие ребра есть в графе. С ее помощью можно эффективно проверить, существует ли ребро между двумя вершинами. Матрицу можно хранить в виде массива:
```cpp
    bool adj[V + 1][V + 1];
```
где элемент adj[a][b] равен 1, если существует ребро, ведущее из вершины a в вершину b, а в противном случае равен 0. Так, матрица смежности для графа на рисунке а имеет вид:
![Текст с описанием картинки](https://watery-orbit-cc0.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fa25a3577-ad33-4031-8821-1716d15d1739%2FUntitled.png?id=1f57fa54-d2b2-447e-9d9c-d3ff87ebf85c&table=block&spaceId=04a2f7a5-16f3-46e7-94be-8d6a3f7074ed&width=450&userId=&cache=v2)
Недостаток матрицы смежности заключается в том, что она содержит $v^2$ элементов, большая часть которых обычно равна 0. Поэтому такое представление не годится для больших графов.

**Список ребер** содержит все ребра графа в некотором порядке. Это представление удобно, если алгоритм обрабатывает все ребра и не требуется находить ребра, начинающиеся в заданной вершине.
Список ребер можно хранить в векторе:

```cpp
// Структура данных для хранения ребра Graph
struct Edge {
    int src, dest;
};
 
// Класс для представления graphического объекта
class Graph
{
public:
    // вектор векторов для представления списка смежности
    vector<vector<int>> adjList;
 
    // Конструктор Graphа
    Graph(vector<Edge> const &edges, int n)
    {
        // изменить размер вектора, чтобы он содержал `n` элементов типа `vector<int>`
        adjList.resize(n);
 
        // добавляем ребра в ориентированный graph
        for (auto &edge: edges)
        {
            // вставляем в конце
            adjList[edge.src].push_back(edge.dest);
 
            // раскомментируйте следующий код для неориентированного Graph
            // adjList[edge.dest].push_back(edge.src);
        }
    }
};
```

## Обход графа: DFS and BFS
В обоих случаях задается начальная вершина и ставится задача посетить все достижимые из нее вершины.
Различие заключается в порядке посещения вершин.

![](https://camo.githubusercontent.com/9a7294a66914257f058315a10f5f92345e4dcca7802e48fb4bb1ab7a85a3efe1/68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f313238302f302a6d694736786479597a647672423637532e676966)

https://www.youtube.com/watch?v=k9cNb5ePN_Y&list=LL&index=7&t=1487s

### BFS - поиск в ширину
Идея - "поджигание" вершин, начиная от стартовой.

Понадобится: 
* очередь, в которую будем помещать элементы по мере их обнаружения. Добавляем в очередь справа, снимаем из очереди слева.
* список посещенных вершин

Итеративный метод:
```cpp
void BFS(Graph const &graph, int v, vector<bool> &discovered)
{
    // создаем queue для выполнения BFS
    queue<int> q;
 
    // помечаем исходную вершину как обнаруженную
    discovered[v] = true;
 
    // поставить исходную вершину в queue
    q.push(v);
 
    // цикл до тех пор, пока queue не станет пустой
    while (!q.empty())
    {
        // удаляем передний узел из очереди и печатаем его
        v = q.front();
        q.pop();
        cout << v << " ";
 
        // делаем для каждого ребра (v, u)
        for (int u: graph.adjList[v])
        {
            if (!discovered[u])
            {
                // помечаем его как обнаруженный и ставим в queue
                discovered[u] = true;
                q.push(u);
            }
        }
    }
}
```

Рекурсивный метод:
```cpp
void recursiveBFS(Graph const &graph, queue<int> &q, vector<bool> &discovered)
{
    if (q.empty()) {
        return;
    }
 
    // удаляем передний узел из очереди и печатаем его
    int v = q.front();
    q.pop();
    cout << v << " ";
 
    // делаем для каждого ребра (v, u)
    for (int u: graph.adjList[v])
    {
        if (!discovered[u])
        {
            // помечаем его как обнаруженный и ставим в queue
            discovered[u] = true;
            q.push(u);
        }
    }
 
    recursiveBFS(graph, q, discovered);
}
```
Временная сложность обхода BFS составляет O(V + E), куда V а также E - общее количество вершин и ребер в Graph соответственно. Обратите внимание, что O(E) может варьироваться между O(1) а также O(V^2), в зависимости от того, насколько плотен graph.

## DFS - поиск в глубину
Идея - продвигаться вглубь, пока это возможно.

Понадобится: 
* стек, в который будем помещать элементы по мере их обнаружения. Добавляем в стек справа, вынимаем из стека справа.
* список посещенных вершин

Итеративный метод:
```cpp
void iterativeDFS(Graph const &graph, int v, vector<bool> &discovered)
{
    // создаем stack, используемый для итеративной DFS
    stack<int> stack;
 
    // помещаем исходный узел в stack
    stack.push(v);
 
    // цикл до тех пор, пока stack не станет пустым
    while (!stack.empty())
    {
        // Извлечь вершину из stack
        v = stack.top();
        stack.pop();
 
        // если вершина уже обнаружена,
        // игнорируй это
        if (discovered[v]) {
            continue;
        }
 
        // мы доберемся сюда, если выскочившая вершина `v` еще не обнаружена;
        // напечатать `v` и обработать его необнаруженные соседние узлы в stack
        discovered[v] = true;
        cout << v << " ";
 
        // делаем для каждого ребра (v, u)
        // мы используем обратный итератор
        for (auto it = graph.adjList[v].rbegin(); it != graph.adjList[v].rend(); it++)
        {
            int u = *it;
            if (!discovered[u]) {
                stack.push(u);
            }
        }
    }
}
```
