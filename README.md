# TDD FizzBuzzWhizz

## 练习描述

我们现在做一个初级的TDD练习，题目需求如下：

你是一名体育老师，在某次课距离下课还有五分钟时，你决定搞一个游戏。此时有100名学生在上课。游戏的规则是：

+ 1、你首先说出三个不同的特殊数，要求必须是个位数，比如3、5、7。
+ 2、让所有学生排成一队，然后按顺序报数。
+ 3、学生报数时，如果所报数字是第一个特殊数（3）的倍数，那么不能说该数字，而要说Fizz；如果所报数字是第二个特殊数（5）的倍数，那么要说Buzz；如果所报数字是第三个特殊数（7）的倍数，那么要说Whizz。
+ 4、学生报数时，如果所报数字同时是两个特殊数的倍数情况下，也要特殊处理，比如第一个特殊数和第二个特殊数的倍数，那么不能说该数字，而是要说FizzBuzz, 以此类推。如果同时是三个特殊数的倍数，那么要说FizzBuzzWhizz。
+ 5、学生报数时，如果所报数字包含了第一个特殊数，那么也不能说该数字，而是要说相应的单词，比如本例中第一个特殊数是3，那么要报13的同学应该说Fizz。如果数字中包含了第一个特殊数，那么忽略规则3和规则4，比如要报35的同学只报Fizz，不报BuzzWhizz。
 
现在，我们需要你完成一个程序来模拟这个游戏，它首先接受学生个数，然后输出这些学生应该报数的数或单词，假定三个特殊数是：3，5，7

输入学生个数：
```
100
```

输出（片段）
```
1
2
Fizz
4
Buzz
Fizz
Whizz
8
Fizz
Buzz
11
Fizz
Fizz
Whizz
FizzBuzz
16
17
Fizz
19
Buzz 
…
一直到100
```

要求：
- 以TDD的方式进行开发，要保证项目提供的集成测试通过，同时自己添加的测试也要通过。

## 环境要求

- Intellij
- Java 8
- Junit 4.12

## 如何开始

- 克隆模版库
- 在 `main`下的`FizzBuzzGame`中完成实现，在`test`下的`FizzBuzzGameTest`中完成测试
- 根目录下执行`./gradlew clean test`，此时所有测试都是失败的
- 开始按照题目要求完成练习

## 如何测试
- 根目录下执行`./gradlew clean test`，查看测试结果

## 输出规范
- 完成需求的代码及测试