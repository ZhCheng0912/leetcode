# leetcode
LeetCode-learn
## 踩坑 No.1
sort 排序
[something]].sort()；
数组里面是字符串时，按照首字母排序，but，时数字时‘110’<'2'
所以一定要加 [1,2,3,45,8,21].sort((a,b)=>a-b);

### ES6语法总结 踩过的坑
数组常用方法
1、去重 
Array.from(new Set()); //但是无法去掉null
Array.from 构建一个新数组，浅拷贝
new Set() 去重
2、arr.reduce
3、filter
4、map
5、every
6、[...arr]简直不要太好用

### 正则表达
