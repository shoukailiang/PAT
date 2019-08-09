# DataStructure

# 线性表
- 顺序表示
    - [顺序表示](https://github.com/shoukailiang/DataStructure/tree/master/List/SqList/SqList.h)
- 链式表示
    - [单链表](https://github.com/shoukailiang/DataStructure/tree/master/List/LinkList/LinkList.h)
    - 特殊链表
        - [双链表](https://github.com/shoukailiang/DataStructure/blob/master/List/DuLinkList/DuLinkList.h)
        - 循环链表
        - 静态链表
# 栈
- 顺序表示
    - [顺序栈]()
- 链式表示
    - [链式栈]()
# 注意事项
在clion中，需要运行哪个就在CmakeLists.txt 中添加进去如
```
add_executable(DataStructure LinkList/LinkList.cpp LinkList/LinkList.h)
```