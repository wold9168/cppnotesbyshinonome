#C++笔记
##C++万能头
C++的万能头一般是指
`#include<bits/stdc++.h>`
##C++const与指针
`const int * pt1;`

pt1是指向int敞亮的指针，指向目标可修改，但指向的目标的值不可修改。

`int * const pt2;`

pt2是指向int变量的常量指针，指向目标不可修改，但指向目标的值可修改。

`const int * const pt3;`

pt3是指向int常量的常量指针，指向目标不可修改，指向目标的值不可修改。

const+变量名|const+类型名
-|:-
常量指针，指向目标不可修改|指向常量的指针，或者说指向“const+类型名”类型的指针。