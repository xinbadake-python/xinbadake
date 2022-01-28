# c
## ctype.h
* isalnum() 如果是字母数字
* isalpha() 如果是字母
* isdigit() 数字
* isblank() 标准空白字符，如空格水平制表符或换行符
* isspace() 空白字符(空格 换行符 换页符 回车符 垂直制表符 水平制表符等)
* islower() 小写字母
* isupper() 大写字母
* ispunct() 标点符号(除空格或字母数字字符以外俄任何可打印字符）
* tolower() 返回小写字符，**不改变字符**
* toupper() 返回大写字符

### 例子
写一个函数，当键入一段字符，返回其中的单词数 行数 总字符数 
```
#include <stdio.h>
#include <ctype.h>
#include <stdbool.h>

int main()
{
  while((c=putchar())!=STOP标志)
  {
    if(isalpha)
    if(!isalpha)
```

