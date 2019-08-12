# DataStructure

# 线性表
- 顺序表示
    - [顺序表示](https://github.com/shoukailiang/DataStructure/blob/dev/List/SqList/SqList.h)
- 链式表示
    - [单链表](https://github.com/shoukailiang/DataStructure/blob/dev/List/LinkList/LinkList.h)
    - 特殊链表
        - [双向链表](https://github.com/shoukailiang/DataStructure/blob/dev/List/DuLinkList/DuLinkList.h)
        - 循环链表
        - 静态链表
# 栈
- 顺序表示
    - [顺序栈](https://github.com/shoukailiang/DataStructure/blob/dev/Stack/SqStack/SqStack.h)
- 链式表示
    - [链式栈](https://github.com/shoukailiang/DataStructure/blob/dev/Stack/LinkStack/LinkStack.h)
- 栈的应用（递归）
- 栈的应用（四则运算表达式求值）
# 队列
- 顺序表示
    - [顺序队列](https://github.com/shoukailiang/DataStructure/blob/dev/Queue/SqQueue/SqQueue.h)
- 链式表示
    - [链式队列](https://github.com/shoukailiang/DataStructure/blob/dev/Queue/LinkQueue/LinkQueue.h)
#数组和广义表

# 树
- [二分搜索树](https://github.com/shoukailiang/DataStructure/blob/dev/Tree/BinarySearchTree/BinarySearchTree.h)
# 图
- [邻接表](https://github.com/shoukailiang/DataStructure/blob/dev/Graph/SparseGraph/SparseGraph.h)
- [邻接矩阵](https://github.com/shoukailiang/DataStructure/blob/dev/Graph/DenseGraph/DenseGraph.h)
# 排序算法
- [选择排序](https://github.com/shoukailiang/DataStructure/blob/dev/Sort/SelectionSort/SelectionSort.cpp)
- [冒泡排序](https://github.com/shoukailiang/DataStructure/blob/dev/Sort/BubbleSort/BubbleSort.cpp)
- [插入排序](https://github.com/shoukailiang/DataStructure/blob/dev/Sort/InsertionSort/InsertionSort.cpp)
- [希尔排序](https://github.com/shoukailiang/DataStructure/blob/dev/Sort/ShellSort/ShellSort.cpp)
# 注意事项
在clion中，需要运行哪个就在CmakeLists.txt 中添加进去如
```
add_executable(DataStructure LinkList/LinkList.cpp LinkList/LinkList.h)
```