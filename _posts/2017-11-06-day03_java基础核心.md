---
    author: 周潘俊
    comments: true
    date: 2017-11-6 22:22:32+00:00
    layout: post
    title: java基础核心
    categories:
    - Works
    - Tech
    tags:
    - java
    - Scanner
    - Random
    - 循环
    ---
#### 1.简述Scanner类及Random类的功能和使用方式？
#
    import java.util.Scanner;//导入包
    import java.util.Random;
    class xxx{
        ...main...{
            Scanner sc = new Scanner(System.in);//创建新对象
            int a = sc.nextInt();//输入一个整数
            String str = sc.next();//输入字符串
            
            Random rd = new Random();
            int b = rd.nextInt(100);//产生随机整数[1,100)
            double c = rd.nextDouble();//产生一个随机小数[0,1)
        }
    }


#### 2.if语句的格式有几种?注意事项是什么?分别在什么时候使用?
#
    1.if(条件){符合条件执行的语句}
    2.if(){}else{}
    3.if(){}else if(){} else if()...else{}
    4.三元表达式  a>b ? a:b

#### 3.for循环、while循环的格式是什么？简述执行流程及注意事项？
#
    for(int i; i<10;i++){语句}
    
    while(true){语句}//加break别死循环了

####   4.简述break、continue的作用？
* break 跳出整个循环
* continue 跳出这次循环，继续执行下一次
switch可以接受byte char short int 类型//最终都自动转为int
1.5版本增加了 enum枚举类型
1.7版本增加了String 类型:编译器后台帮忙哈希成哈希码进行比较

