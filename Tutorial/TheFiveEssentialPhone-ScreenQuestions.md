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

（如果候选人按照他们自己多年的经验和专利能力，觉得问题太简单，不想做这些简单的尝试性问题，你可以告诉他们这些是流程所需，请他们理解。如果他们还是拒绝，则告知他们我们只会面试可以通过电话面试来完成编码的候选人，感谢他们的所花的时间，并挂断电话）

> Give them a few minutes to write and hand-simulate the code. Tell them they need to make it syntactically correct and complete. Make them read the code to you over the phone. Copy down what they read back. Put it into your writeup. If they're sloppy, or don't want to give you exact details, give them one more chance to correct it, and then go with Not Inclined. 



> (Note added 10/6/04) -- another good approach being used by many teams is to give the candidate "homework". E.g. you can give them an hour to solve some coding problem (harder than the ones below) and email the solution to you. Works like a charm. Definitely preferable to reading code over the phone. 

> Anyway, here are some examples. I've given solutions in Java, mostly. I've gone back and forth on accepting solutions in other languages (e.g. Ruby, Perl, Python), and I've decided that candidates need to be able to code their answers in C, C++ or Java. It's wonderful if they know other languages, and in fact those who do tend to do a lot better overall. But to be an Amazon SDE, you need to prove you can do C++ or Java first. 