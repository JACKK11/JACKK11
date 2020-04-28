# 个人基本信息

  - 班级：19级自动化(7)班
  - 姓名：陈也华
  - 学号：3119001097
  - 班内序号：05

# 第5次作业题目

1、基于课程所学，推断以下程序的输出。
（千万不要直接放进编译器跑出答案来，应该是自己去推，写到纸上，然后再编译器验证，推的过程可以翻书）
（本作业要求提交照片，里面有验证前你写在纸上的内容和验证后的修改）

```c
#include <stdio.h>
#include <stdlib.h>
#define M  10.0f
#define N  10.0
int main()
{

    int x='a', y = 'b', z = 'b';
    x = y == z;
    printf("x,y,z = %d,%d,%d\n", x,y,z);
    
    x = (1,6,9), 2, 3;
    printf("x = %d\n", x);
    
    x = 5, y = 10, z = 15;
    z /= x + y;
    printf("z = %d\n", z);
    
    (z /= x) + y;
    printf("z = %d\n", z);
    
    printf("%.1f,%10.2f,%-10.3f,%d,%d\n",95/N,95/M,95/M,sizeof(95/N),sizeof(95/M));

    printf("\\Hello %% world! \\\n");
    
    return 0;
}
``` 

2、自学循环程序结构，完成以下程序。 
提示用户输入行数n，程序按下图效果自动输出n行数字，下图是n为5时的输出效果。
```c
    1
   121
  12321
 1234321
123454321
```
# 作业答案  
![image](https://github.com/JACKK11/JACKK11/raw/master/images/hw5_result1.png)
http://github.com/JACKK11/JACKK11/raw/master/images/hw5_result2.jpg
http://github.com/JACKK11/JACKK11/raw/master/images/hw5_result3.png
http://github.com/JACKK11/JACKK11/raw/master/images/hw5_result4.png

