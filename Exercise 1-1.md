```c
#include <stdio.h>
 
int main(void)//这是注释
{
  printf("hello, world\n");
  return 0;
}
```
void 这个返回值意思是 空的返回值，是微软给c语言添加的一种类型，不是标准c的
你要是使用的是dev-c++，那么你需要下面的代码才可以
以下看上去很标准
```c
#include <stdio.h>
 
int main()//去掉void
{
  printf("hello, world\n");
  return 0;
}
```
