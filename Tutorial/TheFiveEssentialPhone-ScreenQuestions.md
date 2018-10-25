# The Five Essential Phone-Screen Questions

[Stevey's Drunken Blog Rants™](https://sites.google.com/site/steveyegge2/blog-rants)

> I've been on a lot of SDE interview loops lately where the candidate failed miserably: not-inclined votes all around, even from the phone screeners who brought the person in initially. 

最近我参加了几轮高级软件开发工程师的面试，但很多候选人都不幸失败了：周围全是不赞成，即便是最初推荐候选人的电话面试官，都投了否定票。

> It's usually pretty obvious when the candidate should have been eliminated during the phone screens. Well, it's obvious in retrospect, anyway: during the interviews, we find some horrible flaw in the candidate which, had anyone thought to ask about it during the phone screen, would surely have disqualified the person. 

通常情况下，很明显这些候选人在电话面试时就应该被淘汰。不管怎么说，回想起来还是很明显的: 在面试过程中，我们发现了候选人身上的一些可怕的缺陷，如果有人想在电话面试时问这些问题，那么这个人肯定会被取消面试资格。

> But we didn't ask. So the candidate came in for interviews and wound up wasting everyone's time. 

但我们没有问，所以候选人来参与面试，最终浪费大家的时间。



## 反模式（Antipatterns）

> I've done informal postmortems on at least a hundred phone screens, many of them my own. Whenever a candidate bombs the interviews, I want to know what went wrong with the screen. And guess what? A pattern has emerged. Two patterns, actually.

我对至少100次电话面试做过非正式的事后分析，其实很多都是我自己的。当候选人把一场面试搞砸时，我想知道到底哪里出错了。你猜怎样？一种模式出现了，事实上，是两种模式。

> The first pattern is that for most failed phone screens, *the candidate did most of the talking.* The screener only asked about stuff on the candidate's resume, and the candidate was able to talk with passion and enthusiasm about this incredibly cool thing they did, blah blah blah, and the screener was duly impressed. 

第一种模式是，对于多数电话面试，候选人一直在说，面试官只问候选人简历上的内容，而候选人满怀激情的谈论他们所做的非常酷的事情，等等等等，面试官对此印象深刻。

> That's how many/most phone screens go wrong. 

这就是很多或者说绝大多数电话面试是如何变糟的。

> The right way to do a phone screen is to do most of the talking, or at least the driving. You look for specific answers, and you guide the conversation along until you've got the answer or you've decided the candidate doesn't know it. Whenever I forget this, and get lazy and let the candidate drone on about their XML weasel-pin connector project, I wind up bringing in a dud. 

完成电话面试的正确方式应该是面试官来做大部分谈话，或者至少主导谈话过程。你寻求特定的答案，你需要引导谈话过程，直到你得到了答案或者判断候出选人并不知道答案。每当我忘了这一点，或者变懒而被候选人用他们的XML weasel-pin connector项目牵着走，电话面试最终功亏一篑。

> The second pattern is that *one-trick ponies only know one trick.* Candidates who have programmed mostly in a single language (e.g. C/C++), platform (e.g. AIX) or framework (e.g. J2EE) usually have major, gaping holes in their skills lineup. These candidates will fail their interviews here because our interviews cover a broad range of skill areas. 

第二种模式是，只有一技之长的人真的只知道一技之长。多数时间使用一种语言（例如C/C++）、一个平台（例如AIX）或者框架（例如J2EE）进行开发的候选人，他们的技能序列是有很大缺陷的。由于我们的面试涵盖广泛的技能领域，这些候选人会在面试中失败。

> These two phone screen (anti-)patterns are related: if you only ask the candidate about what they know, you've got a fairly narrow view of their abilities. And you're setting yourself up for a postmortem on your phone screen.

这两种电话面试的（反）模式是相互联系的。如果你只问候选人知道的东西，你对他们的能力的看法会非常狭隘。也会在之后做电话面试事后分析时，让自己深陷困境。



## Acid测试(Acid Tests)

> In an effort to make life simpler for phone screeners, I've put together this list of Five Essential Questions that you need to ask during an SDE screen. They won't guarantee that your candidate will be great, but they will help eliminate a huge number of candidates who are slipping through our process today. 

为了让电话面试更简单，我把面试软件开发工程师时五项必问的问题裂了出来。这些问题虽然不能保证筛选出的候选人都很优秀，但是却可以帮助我们筛掉大量想蒙混过关的候选人。

> These five areas are litmus tests -- very good ones. I've chosen them based on the following criteria: 

这五个方面是整体看法，非常好。我按照以下标准选择了它们。

> 1) They're universal - every programmer needs to know them, regardless of experience, so you can use them in all SDE phone screens, from college hires through 30-year veterans. 
>
> 2) They're quick - they're areas that you can probe very quickly, without eating too much into your phone-screen time. Each area can be assessed with 1 to 5 minutes of "weeder questions", and each area has almost unlimited weeder questions to choose from. 
>
> 3) They're predictors - there are certain common "SDE profiles" that are easy to spot because they tend to fail (and I mean really fail) in one or more of these five areas. So the areas are amazingly good at weeding out bad candidates. 

1）通用的 —— 每个程序员都需要了解它们，从校园招聘到社招30岁的老员工，无论经验如何，这样你就可以在所有的SDE电话面试中使用它们。

2）快速的 —— 不需要占用太多电话面试时间，你可以快速探测。每个方面可以利用1到5分钟的“除草问题”进行评估，而每个方面又有几乎无限的除草问题可供选择。

3）可预测的 —— 有些常见的“SDE剖面”可以很容易被发现，因为这些很容易在五个方面问题中的一个或多个问题中失败。所以，这些方面可以非常好的剔除掉不良候选人。

> You have to probe all five areas; you can't skip any of them. Each area is a proxy for a huge body of knowledge, and failing it very likely means failing the interviews, even though the candidate did fine in the other areas. 

你需要探查全部五个方面，不可跳过。因为每个领域都包含大量的知识，所以，即便是候选人在其他方面做的不错，但也可能意味着会面试失败。

> Without further ado, here they are: The Five Essential Questions for the first phone-screen with an SDE candidate: 

闲言少叙，这就是电话面试软件开发工程师候选人的五项基本问题：

> 1) Coding. The candidate has to write some simple code, with correct syntax, in C, C++, or Java.
> 2) OO design. The candidate has to define basic OO concepts, and come up with classes to model a
> simple problem.
> 3) Scripting and regexes. The candidate has to describe how to find the phone numbers in 50,000
> HTML pages.
> 4) Data structures. The candidate has to demonstrate basic knowledge of the most common data
> structures.
> 5) Bits and bytes. The candidate has to answer simple questions about bits, bytes, and binary
> numbers.

1）写代码：候选人需要用C, C++或Java写一些简单的语法正确的代码；

2）面向对象设计：候选人需说明面向对象的基本概念，并能够针对某个简单问题，使用类建模。

3）脚本和表达式：例如请候选人描述出如何从50000个HTML页面中，找出所有电话号码；

4）数据结构：候选人需展示常见数据结构的基本知识；

5）比特&字节：候选人需回答一些关于位、字节和二进制数运算的基本问题；

>what I'm looking for here is a total vacuum in one of these areas. It's OK if they
>struggle a little and then figure it out. It's OK if they need some minor hints or prompting. I don't mind
>if they're rusty or slow. What you're looking for is candidates who are utterly clueless, or horribly
>confused, about the area in question.

我寻找的是在这个领域完全空白的候选人。如果他们挣扎一下然后能够解决是可以的，或者需要一点提示或建议才能解决也是可以的。我不介意他们愚钝或者速度慢。你需要发现的是那些无所适从，或者完全不清楚这些问题的那些候选人。

> For example, you may find a candidate who decides that a Vehicle class should be a subclass of ParkingGarage, since garages contain cars. This is just busted, and it's un-fixable in any reasonable amount of training time. 

例如，你会遇到一些候选人，将汽车类作为停车场的子类，因为停车场包含汽车。这就是问题，无论花多少合理的训练时间都无法解决。

> Or a candidate might decide, when asked to search for phone numbers in a bunch of text files, to write a 2000-line C++ program, at which point you discover they've never heard of "grep", or at least never used it. 

或者当候选人被问到在一堆文本文件中搜索电话号码时，他决定写一段2000行的C++程序，从这一点上，也告诉你，他们从来没有听过“grep”或者至少从来没使用过。

> When a candidate is totally incompetent in one of these Big Five areas, the chances are very high that they'll bomb horribly when presented with our typical interview questions. Last week I interviewed an SDE-2 candidate who made both of the mistakes above (a vehicle inheriting from garage, and the 2000-line C++ grep implementation.) He was by no means unusual, even for the past month. We've been bringing in many totally unqualified candidates. 

或者当发现一个候选人在这5个关键方面中的任何一个都无能为力，那么他们在面对常规面试问题时，成功的几率也十分渺茫。上周我面试了一个犯了上面两种错误（汽车继承自车库，写2000行grep代码）的SDE-2候选人，在过去一个月中，他并不特别，我们引入了太多不合格的候选人。

> The rest of this document describes each area in more detail, and gives example questions, and solutions. 

下面的文章中，会详细介绍每个方面，给出一些示例问题和解答。



## 一、 编码

> The candidate has to write some code. Give them a coding problem that requires writing a short, straightforward function. They can write it in whatever language they like, as long as they don't just call a library function that does it for them. 

候选人必须写代码。给出一个问题，书写一个简短的函数。可以自选书写语言，只要不直接调用系统库函数来帮他们完成就可以。

> It should be a trivial problem, one that even a slow candidate can answer in 5 minutes or less. 

这个问题应该是个很小的问题，即便是一个愚钝的候选人，也可以在5分钟或更少时间都能给出答案。

> (If the candidate seems insulted by the thought of having to get their hands dirty with a trivial coding question, after all their years of experience, patents, etc., tell them it's required procedure and ask them to humor you. If they refuse, tell them we only interview people who can demonstrate coding skills over the phone, thank them for their time, and end the call.) 

（如果候选人根据他们自己多年的经验和能力，觉得问题太简单，不想做这些简单的尝试性问题，你可以告诉他们这些是流程所需，请他们理解。如果他们还是拒绝，则告知他们我们只会面试可以通过电话面试来完成编码的候选人，感谢他们的所花的时间，并挂断电话）

> Give them a few minutes to write and hand-simulate the code. Tell them they need to make it syntactically correct and complete. Make them read the code to you over the phone. Copy down what they read back. Put it into your writeup. If they're sloppy, or don't want to give you exact details, give them one more chance to correct it, and then go with Not Inclined. 

给他们几分钟书写和手动模拟代码，告诉他们写的代码需要语法正确且完整。让他们在电话中将代码读给你，你来记录到面试记录中，如果模糊不清，请他们详细的讲述细节并再给一次机会更正模糊的地方，然后继续进行。

> (Note added 10/6/04) -- another good approach being used by many teams is to give the candidate "homework". E.g. you can give them an hour to solve some coding problem (harder than the ones below) and email the solution to you. Works like a charm. Definitely preferable to reading code over the phone. 

(注解添加于 10/6/04) -- 另一种比较好，也被很多开发组使用的方式是给候选人留家庭作业。例如，可以给他们一小时时间来解决一些编码难题（要难于下面这些问题），然后请他们把解决方案通过电子邮件发送过来。这种方式更酷，也比通过电话来朗读代码更可取。

> Anyway, here are some examples. I've given solutions in Java, mostly. I've gone back and forth on accepting solutions in other languages (e.g. Ruby, Perl, Python), and I've decided that candidates need to be able to code their answers in C, C++ or Java. It's wonderful if they know other languages, and in fact those who do tend to do a lot better overall. But to be an Amazon SDE, you need to prove you can do C++ or Java first. 

不管怎样，这有些示例，大多我都已经给出了Java的实现方案。我反复看了其他语言（例如：Ruby、Perl、Python）可接受的解决方案，我认为候选人需要能够使用C、C++或Java实现出他们的答案，如果他们知道其他语言，而且事实上如果他们还能用其他语言来实现，总体上他们会做的更好。但是，如果想成为亚马逊的软件开发工程师，你首先需要会用C++或Java。

**Example 1**: Write a function to reverse a string. （翻转字符串）

Example Java code: 

```objective-c
public static String reverse ( String s ) {
    int length = s.length(), last = length - 1;
    char[] chars = s.toCharArray();
    for ( int i = 0; i < length/2; i++ ) {
        char c = chars[i];
        chars[i] = chars[last - i];
        chars[last - i] = c;
    }
    return new String(chars);
}
```

> Example output for "Madam, I'm Adam": madA m'I ,madaM 



**Example 2**: Write function to compute Nth fibonacci number: （打印第N个斐波拉契数列的值）

Java and C/C++: 

```objective-c
static long fib(int n) {
    return n <= 1 ? n : fib(n-1) + fib(n-2);
}
```



(Java Test Harness) 

```java
public static void main ( String[] args ) {
    for ( int i = 0; i < 10; i++ ) {
        System.out.print ( fib(i) + ", " );
    }
    System.out.println ( fib(10) );
}
```



(C/C++ Test Harness) 

```c++
main () {
	for ( int i = 0; i < 10; i++ ) {
		printf ( "%d, ", fib(i) );
	}
    printf ( "%d\n", fib(10) );
}
```

> Test harness output:
>  0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55



**Example 3**: Print out the grade-school multiplication table up to 12x12（12x12的乘法表）

Java: (similar for C/C++) 

```java
public static void multTables ( int max ) {
	for ( int i = 1; i <= max; i++ ) {
        for ( int j = 1; j <= max; j++ ) {
            System.out.print ( String.format ( "%4d", j * i ));
        }
        System.out.println();
    }
}
```

> Example output:
>
> 1	2	3	4 	5 	6 	7	8	9	10	11	12
> 2	4	6	8	10	12	14	16	18	20	22	24
> 3	6	9	12	15	18	21	24	27	30	33	36
> 4 	8	12	16	20	24	28	32	36	40	44	48
> 5	10	15	20	25	30	35	40	45	50	55	60
> 6	12	18	24	30	36	42	48	54	60	66	72
> 7	14	21	28	35	42	49	56	63	70	77	84
> 8	16	24	32	40	48	56	64	72	80	88	96
> 9	18	27	36	45	54	63	72	81	90	99	108
> 10	20	30	40	50	60	70	80	90	100	110	120
> 11	22	33	44	55	66	77	88	99	110	121	132
> 12	24	36	48	60	72	84	96	108	120	132	144



**Example 4**: Write a function that sums up integers from a text file, one int per line.（计算文件中每行的数的和）

 Java: 

```java
public static void sumFile ( String name ) {
    try {
        int total = 0;
        BufferedReader in = new BufferedReader ( new FileReader ( name ));
        for ( String s = in.readLine(); s != null; s = in.readLine() ) {
            total += Integer.parseInt ( s );
        }
        System.out.println ( total );
        in.close();
    } catch ( Exception xc ) {
        xc.printStackTrace();
    }
}     
```



**Example 5**: Write function to print the odd numbers from 1 to 99. （打印1-99的奇数）

C/C++: 

```c++
void printOdds() {
    for (int i = 1; i < 100; i += 2) {
        printf ("%d\n", i); // or cout << i << endl;
    }
}
```

Java: 

```java
public static void printOdds() {
    for (int i = 1; i < 100; i += 2) {
        System.out.println ( i );
    }
} 
```



**Example 6**: Find the largest int value in an int array.（找到数组中最大整数值）

 Java: 

```java
public static int largest ( int[] input ) {
    int max = Integer.MIN_VALUE;
    for ( int i = 0; i < input.length; i++ ) {
        if ( input[i] > max ) max = input[i];
    }
    return max;
}
```



**Example 7**: Format an RGB value (three 1-byte numbers) as a 6-digit hexadecimal string. （将三字节的RGB数值，转化为6位十六进制字符串）

 Java: 

```java
public String formatRGB ( int r, int g, int b ) {
    return (toHex(r) + toHex(g) + toHex(b)).toUpperCase();
} 
    
public String toHex ( int c ) {
    String s = Integer.toHexString ( c );
    return ( s.length() == 1 ) ? "0" + s : s;
} 
```

Or in Java 1.5: 

```java
public String formatRGB ( int r, int g, int b ) {
	return String.format ( "%02X%02X%02X", r, g, b );
}
```

> Example output for (255, 0, 128):



> You can ask any question you like; doesn't have to be one of the ones above. They're just examples. 

除了上述问题外，你可以问任何你想问的问题，这些只是例子。

> Some properties of a good weeder phone-screen coding question are: 
>
> 1. It's simple. It has to be something that you should be able to solve, trivially, in about 2 minutes or less. Not too tricky. Basic stuff. 
> 2. You've solved it. You shouldn't ask a question unless you've solved it yourself recently, so you know it's a reasonable question, and you can evaluate their answer to it. You should consider coding it yourself during the time you've given them to do it. 
> 3. It has loops or recursion. Recursion is actually preferable. Being able to reason recursively or inductively is important for many areas of computing, including using heirarchical data representations (e.g. XML), distributed computing, searching, and sorting. Many candidates simply can't think recursively, and this often goes undetected until interview-time. Try to find out at compile-time! Er, phone-screen time, that is. 
> 4. It has formatted output. This is a basic skill, useful for debugging, simple report generation, and lots of other things. "printf" is a universal standard; it exists in C, C++, Java, Perl, Ruby, Python, and virtually every other mainstream language, at least as a library call. Like file I/O, it's a good indicator as to whether the candidate has written "real" code before. 
> 5. It has text-file I/O. Candidates who have worked in frameworks for too long often become unable to function as programmers outside that framework. Not being able to do simple file I/O is a common indicator that they've grown overly dependent on a particular framework. 

一个好的电话面试筛选问题有以下特性：

1. 简单。2分钟甚至更少时间能够解答出来，不刁钻，而且是基本的问题；
2. 你自己能够解答。你问的问题需要是你自己最近已经解答过的问题，因此你知道问题是合理的，而且你可以评估候选人给出的答案怎么样，在让他们写出来的时间内，你自己也要尝试着去实现写出来。
3. 有循环和递归。递归更好，能够递归推理或归纳推理对于计算的许多领域都很重要，包括使用层次数据表示(例如XML)、分布式计算，搜索和排序。许多求职者根本无法进行递归思考，而这往往在面试时才被发现。尝试模拟编译时才发现问题，恰好还是电话面试时间。
4. 格式化输出。这是基本的技能，对于调试代码，简单报告生成和其他很多东西都有用。“printf”就是个通用标准；它存在于C、C++、Java、Perl、Ruby、Python和几乎其他主流语言中，至少是作为库调用。像文件I/O操作就可以很好的表明候选人是不是真的写过代码。
5. 有文本文件IO。如果候选人长期在开发Framework，会变得在Framework之外不清楚应该如何工作。不能够操作简单的文件IO往往表明他们过度依赖于特定框架。

> It's hard to cover all these things and still be a short weeder question. If you think of a question that has all these properties, let me know. 

一个简短的“除杂草”问题很难能够包含所有的方面。如果你认为一个问题能够包含这些所有的方面，请告诉我。



## 二、面向对象编程

> We shouldn't hire SDEs (arguably excepting college hires) who aren't at least somewhat proficient with OOP. I'm not claiming that OOP is good or bad; I'm just saying you have to know it, just like you have to know the things you can and can't do at an airport security checkpoint. 



> Two reasons: 
>
> 1. OO has been popular/mainstream for more than 20 years. Virtually every programming language supports OOP in some way. You can't work on a big code base without running into it. 
> 2. OO concepts are an important building block for creating good service interfaces. They represent a shared understanding and a common vocabulary that are sometimes useful when talking about architecture. 



> So you have to ask candidates some OO stuff on the phone. 



### 1. Terminology

> The candidate should be able to give satisfactory definitions for a random selection of the following terms: 
>
> 1. class, object (and the difference between the two) 
> 2. instantiation
> 3. method (as opposed to, say, a C function)
> 4. virtual method, pure virtual method 
> 5. class/static method
> 6. static/class initializer
> 7. constructor
> 8. destructor/finalizer
> 9. superclass or base class
> 10. subclass or derived class
> 11. inheritance
> 12. encapsulation
> 13. multiple inheritance (and give an example)
> 14. delegation/forwarding
> 15. composition/aggregation
> 16. abstract class
> 17. interface/protocol (and different from abstract class)
> 18. method overriding
> 19. method overloading (and difference from overriding)
> 20. polymorphism (without resorting to examples)
> 21. is-a versus has-a relationships (with examples)
> 22. method signatures (what's included in one)
> 23. method visibility (e.g. public/private/other)



> These are just the bare basics of OO. Candidates should know this stuff cold. It's not even a complete list; it's just off the top of my head. 



> Again, I'm not advocating OOP, or saying anything about it, other than that it's ubiquitious so you have to know it. You can learn this stuff by reading a single book and writing a little code, so no SDE candidate (except maybe a brand-new college hire) can be excused for not knowing this stuff. 



> I draw a distinction between "knows it" and "is smart enough to learn it." Normally I allow people through for interviews if they've got a gap in their knowledge, as long as I think they're smart enough to make it up on the job. 



> But for these five areas, I expect candidates to know them. It's not just a matter of being smart enough to learn them. There's a certain amount of common sense involved; I can't imagine coming to interview at Amazon and not having brushed up on OOP, for example. But these areas are also so fundamental that they serve as real indicators of how the person will do on the job here. 

### 2. OO Design

This is where most candidates fail with OO. They can recite the textbook definitions, and then go on to 

produce certifiably insane class designs for simple problems. For instance: 

They may have Person multiple-inherit from Head, Body, Arm, and Leg.
 They may have Car and Motorcycle inherit from Garage.
 They may produce an elaborate class tree for Animals, and then declare an enum ("Lion = 1, Bear = 2", etc.) to represent the type of each animal.
 They may have exactly one static instance of every class in their system. 

(All these examples are from real candidates I've interviewed in the past 3 weeks.) 

Candidates who've only studied the terminology without ever doing any OOP often don't really get it. When they go to produce classes or code, they don't understand the difference between a static member and an instance member, and they'll use them interchangeably. 

Or they won't understand when to use a subclass versus an attribute or property, and they'll assert firmly that a car with a bumper sticker is a subclass of car. (Yep, 2 candidates have told me that in the last 2 weeks.) 

Some don't understand that objects are supposed to know how to take care of themselves. They'll create a bunch of classes with nothing but data, getters, and setters (i.e., basically C structs), and some Manager classes that contain all the logic (i.e., basically C functions), and voila, they've implemented procedural programming perfectly using classes. 

Or they won't understand the difference between a char*, an object, and an enum. Or they'll think polymorphism is the same as inheritance. Or they'll have any number of other fuzzy, weird conceptual errors, and their designs will be fuzzy and weird as well. 

For the OO-design weeder question, have them describe: 

1. What classes they would define.

2. What methods go in each class (including signatures).

3. What the class constructors are responsible for.

4. What data structures the class will have to maintain.

5. Whether any Design Patterns are applicable to this problem.

Here are some examples: 

1. Design a deck of cards that can be used for different card game applications. 

   Likely classes: a Deck, a Card, a Hand, a Board, and possibly Rank and Suit. Drill down on who's responsible for creating new Decks, where they get shuffled, how you deal cards, etc. Do you need a different instance for every card in a casino in Vegas? 

2. Model the Animal kingdom as a class system, for use in a Virtual Zoo program. 

   Possible sub-issues: do they know the animal kingdom at all? (I.e. common sense.) What properties and methods do they immediately think are the most important? Do they use abstract classes and/or interfaces to represent shared stuff? How do they handle the multiple-inheritance problem posed by, say, a tomato (fruit or veggie?), a sponge (animal or plant?), or a mule (donkey or horse?) 

3. Create a class design to represent a filesystem. 

   Do they even know what a filesystem is, and what services it provides? Likely classes: Filesystem, Directory, File, Permission. What's their relationship? How do you differentiate between text and binary files, or do you need to? What about executable files? How do they model a Directory containing many files? Do they use a data structure for it? Which one, and what performance tradeoffs does it have? 

4. Design an OO representation to model HTML. 

   How do they represent tags and content? What about containment relationships? Bonus points if they know that this has already been done a bunch of times, e.g. with DOM. But they still have to describe it. 

The following commonly-asked OO design interview questions are probably too involved to be good phone-screen weeders: 

1. Design a parking garage.

2. Design a bank of elevators in a skyscraper.
3. Model the monorail system at Disney World.
4. Design a restaurant-reservation system.

5. Design a hotel room-reservation system.

A good OO design question can test coding, design, domain knowledge, OO principles, and so on. A good weeder question should probably just target whether they know when to use subtypes, attributes, and containment. 