# pinyin-regular-expression
A summary of regular expressions used to identify pinyin.  
一些用于匹配拼音的正则表达式的汇总


# description
检测一个字符串是不是拼音，如'zao','zaoshanghao'等等，来源于stackoverflow


# source
1. example1:  
https://stackoverflow.com/questions/20736291/regex-for-matching-pinyin  
https://stackoverflow.com/questions/24017927/regex-for-matching-numeral-pinyin
2. example2:  
https://stackoverflow.com/questions/17156967/optimizing-a-regular-expression-to-parse-chinese-pinyin


# use
将待测字符串传入regex_pinyin_example1或regex_pinyin_example2  
example:  
```python
test_str1='nihao'  
test_str2='hello'  
res1=regex_pinyin_example1(est_str1)  
res2=regex_pinyin_example1(est_str2)
print(res1)
print(res2)
```
result:
```python 
True  
False
```


# future
持续更新中...

