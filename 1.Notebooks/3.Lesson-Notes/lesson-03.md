# **Reorganize the in-class lesson notes from live video_20190601**
## 1

开始了，我们已经上了2节课了，python部分已经讲完了，然后，后面还有3节是讲数学，然后，Python这部分我们还有些作业，今天，放学的时候会把link发给大家去git pull一下去写那些作业，基本上就是我们昨天和上个星期学习的那些python内容，我们可以简单的回顾一下，就是，我们把这个python放在数学前面是因为我们在这个数学的课里面会用到它，也就是说，我们是把它当一个工具来用的，所以，在某种程度上来说，它是一个工具的话，你只要可以开始用它就好了，一点一点的积累，没有必要一下都学会一下，都学完，数学也是一样的，我们现在讲的这些数学，是为后面的课都要准备用的，是后面课程的一个工具，其实数学本身也是一种工具，就大家也可以把它当成一个工具来看待，也不用一下子都搞懂，然后，拿过来可以上手用就好了，我们只讲大概我们这个课程会用到的部分，其实我觉得到这个今天讲数学的部分，他应该比前两天要简单，前两天讲的python各种各样的库简单，因为，就是我不是很好去，估计大家的难易的感觉，因为有些人觉得python很简单，实际上我觉得这个课不用上python的部分，然后，是因为要自己熟悉的部分和自己不熟悉的部分，我是觉得数学非常重要，因为就是你有可能也不用python，你也可以用其他的语言，但是唯一不变的是这些基本的原理，但数学这个部分呢，我其实做这个奖励的时候就有一点犹豫，因为，好像我们讲的这些东西，按照它这个课程大纲讲的这些东西都太基础了，一会他就会发现，我们好像在回顾一些中学的数学，你们可能也看过了，为什么要拿初中学的数学来看一遍？所以我就根据大家的反馈吧，如果大家觉得这些东西我们不用讲的这么仔细，我就讲的快速把它skip过去，然后讲一些有意思的东西，或者是，我觉得这个很重要，这也挺有意思的，我们就按部就班的把这个过完，大家反馈出来，所以中午的时候我就会调整一下，然后，这可能其实对于你们来说，比较简单一点因为，python这些课里面还有一些练习，你要自己试一试，写写code，但是，数学这个部分只是看就这样了，但是，我觉得数学是这样的，就是，你不太可能通过看一个课，去听一个人讲的，把这个数学学会，你有两种方法去真正的明白，一种方法用的最多，就是你去做一些练习，你动手，你拿纸和笔，在草稿纸上去做推导，做一些运算，另外一种办法就是，你努力去建立一些，insect的东西，这些东西呢？有可能通过你非常多自己的练习，也有可能你很简单的你看了一个非常好的材料，然后你忽然明白这个数学原理，他们之间有互相紧密的联系，下午的时候如果有时间，我会给大家看两个比较有趣的数学的话题，跟咱们的课程有点关系，但比较有趣的话题，然后，最后结束的时候，我们还会再回顾一下，巩固一下我们学的python，讲一讲作业，开始吧，我们从最简单的开始，解方程，你知道数学发展的时候，他有很多条线索，他有一些东西完全是从实际生活里面来的，然后，比方说，你如果去关注一下数学历史的话，你最早发明的数学是几何，和生产有关系，建立起来的这个，然后，还有一类就是，纯粹关注一个数，就是数的运算，你看我们今天这个课，会覆盖一元方程，方程组，然后，多元方程，如果在几何空间里面，就是可以把它们做一个对应，就是比方说，你想求一个像这样的方程，他其实是一个点，它可以抽象成一个点，然后对那种方程组来，你可以把它想象成两个线，求出一个焦点，高斯方程你可以把它想象成求一个曲线，一个曲线其实是跟一个坐标轴，一条直线的交点，然后如果是多元多次方程，他其实是在一个曲面上，求一个截面，或者是一个截线，我们先看一下这个简单的例子，反正大家看看就能看懂，解这个方程。

## 2

然后我们写完这个方程以后我们怎么用一下我们刚刚掌握的工具，我们可以在上面写一个测试，写一个test,如果我们大家做软件开发的话，其实我们等于写了一个search，如果我这个解是对的，我们刚才解出来是-41，算出来应该是OK的。这个是刚才的X前面没有洗漱，把这个左边这个-2给消掉，然后除以下得出来一个解。其实对于系数来说这是一个整数，小数，分数都无所谓，我们是一样去处理的。前面我们处理3，现在我们处理1/3.这个就有点复杂，我们需要做同类项的合并，第一步是把右边的-1搞到左边来，第二步把左边的3x放到右边去，就算出来这个结果。这是一个更复杂的例子，先把这个式子拆成一项一项的，然后再把他们合并起来，最后也可以算出一个解来。现在来想我们线性方程，刚才方程解出来是一个值，其实就是算出来一个点，然后线性方程就不是一个值了，他其实就是一个线，你可以在某种程度上把他理解为一个函数，表示y和x的关系，这是一个线性方程。然后我们用昨天学的numpy还有这个列表，函数打印出来，函数有很多表现形式，一种方式就是你可以写一个公式，像刚才的这种解，另外一种方式就是你画一个表格，x,y,一旦你可以把这个表格画出来，我们昨天画的散点图，如果你散点画的足够密的话，你就会看到一条连续的光滑的曲线，我们把这个式子抄上，把这些打印出来。然后画一个线出来，大家注意一下，你们可能没有观察到这一点，就是x轴，y轴是在这里，。画这个图是为了介绍下面这个概念，截距.然后我们把坐标轴画出来，昨天学的matplot，我们现在是画一条线，灰色的线，然后我们下一步要算这两个点，x轴和y轴的交点，我们jupyter他整个是个file，其实在上一步已经算过x和y了，所以他x和y内存里面是有的。我们这节课应该只用matplot，我们把两个截距算出来，截距就是跟x和y轴的交点，第一步把y等于0带进去然后把x算出来，是-4/3，把x等于零带进去，y是-2.然后我们就直接把这个值标上 ，这两个点放大了。昨天有同学问我能不能动态放，不行啊。我给大家看一下这个东西可以在这里操作的。所以有两个截距就有两个解了，然后我把这两个点连成一个直线。
然后斜率，这里出现几个数字，他其实是两组数，你算斜率的时候不一定非得要截距算斜率，只要是直线上两点，两个不一样他们能减出差来就好。我们在直线上挑了两个点，算出来，口算也能算出来，是1.5，二分之三，然后我们再画一个图，再可视化一下，这个图就比较全了，这里有斜率有截距，这里一小段给标出来，截距之间的。其实我没有过这些。这些差不多几十个code,也都没有什么逻辑，像申明一样，指定好，然后这个工具，加上我们的python，numpy，大家可以用我们程序语言的库去帮助自己理解一些数学的概念，比方说这里有个数学公式，我们用个程序把他画出来，我可以看到结果。好，这是一个放大的图，刚才红色这一小段我把他放大，这是我们两个截距，一个是4/3，一个是-2.。我们斜率直线这些概念可以给直线一个统一的形式。原来我们是这样写的，我们就把他统一一下，一律改成斜率乘以x，然后截距，这是他几何的含义，然后这种形式你会很多很多次看到，所谓线性的关系，为什么线性的关系非常重要呢，现行的关系其实是最简单的，而且他是我们后面用的关系的一些基础，你可以把线性方程做这样一个理解，我只不过这里缺了一个指数，我认为他是一个曲线，正好是一个直的曲线，拿很多曲线去模拟一个函数，然后我们把这个方程再用刚才求出来的这个，然后我们现在再往前跳一步，有了这个直线的定义，线性方程组，直线的交点，我这里写了两个因为最明显，两条线如果不平行的话肯定有交点，但是如果两条线是平行的，那怎么用数学来解释他，怎么用数学来解释他，斜率是一样的，只是截距不一样，相当于你information少了一个，原来你是有两个截距，现在你information少了一个，所以你求不出解来。画了两条线，然后我们就用这两点连一线的方式。解一下个方程，一开始把x消掉，搞出一个负的10x来，这边乘以-10，然后把这一项给减掉，然后把他带回去，就解出来了，然后我们验证一下。
现在我们再训练刚才另外一个发展的方向性，我们谈到的指数，如果大家有我忘了这个数学概念，你们可以打断啊，我们算一下平方根，立方根，注意这里有个点，没有就不是浮点数了。对数其实就是指数的逆运算，都是对称的，写成一个log，你们可以算一下，以4为底16的对数，答案是2.，并不是说以任意数为底，最多是自然对数，然后这是第一个出现的神奇的数，为什么选它，自然对数，这是比较特殊的曲线。我们画出来这个曲线以后，我们在每个点上切它一下，我听过这一个点做个切线，这个切线就有一个斜率，然后我们就把这个斜率记成另外一个数值，这个点有一个y,这个点还有一个斜率，e^x这个函数，他x和y的斜率是一样的，他在任何一个点都是一样的，这意味着对他求导数，他还是本身。他是一个这样的逻辑。

## 3

然后你就计算，有两种情况，第一种情况是他要不然和线相交， 我设的这个线正好一样，这可以做一些验证。如果你知道这个数学规律，像我们昨天做过的这个类似的事情，我们把上海华东地区人的身高，体重的均值，标准差拿出来，我们就拿这两个数做一个正态分布，然后因为我们知道这两个数是非常关键的，我们就可以模拟出来，然后上海地区整个的男性身高体重，然后算了一个5000个人的均值和标准差，反复不停地应用这个比例，然后我要模拟山脉，你去建模一个山脉是很困难的，因为山很复杂，有各种各样的岩石，你可能需要无数多小的面片去建模这个山脉，而且你要让他逼真，看起来像座山，也挺有挑战的。神奇的数字让我们感到很吃惊，到处都是他，算一下求对数公式，（学生提问为什幺要用到这些概念？）算利息的时候就用的到，如果计算复利的话马上就用得到，需要多少年你就能赚到多少倍，这就是对数。只不过换了一个更简洁的表达形式，所有的加都有意义，因为所有的基础是加，所有有计量的地方，需要量化的地方，加都是有意义的。
在物理世界里这是没有规律的，你可以想象这些基本的物理规律，万有引力，他不是线性的，他是跟距离平方成比例关系的，成反比，这里就引入了一个指数的概念。所以你要把周围天体，画一个引力的值，你就不能用这个，因为你画出来的坐标轴会拉的很长，我们下午如果有时间我给大家share一个类似的东西，这是无处不在的，包括速度，速度跟阻力的关系，还有光照，离灯光的距离跟我接收到能量的关系，其实无处不在的你可以去量化的关系，都是一个多项式，一个多项式包括很多成分，一次方只是他一种特殊的情况，我们是首先是拿这个特殊的情况去猜，是不是这个规律。
这个幂运算，表达起来比较复杂一点，把一个x的四次方都拆开来，也是一样的，就是这个含义，幂运算做乘法的时候是把指数相加的，变成了一个这样的东西，然后我们也画一下，把点列出来，你会发现这个东西出现过一次，刚才我们画直线的时候也写过一次，你是看不出来的，你只看到两列数，你把它画出来你就明白了。这是一个曲线，跟我们昨天画的像倒过来了一样，其实不一样，这个没有趋近值的东西，你看这一小段以为很像。这个指数增长，你在现实生活中遇到很多运算，大部分其实是在线性范围里面，你对这种指数没有概念，这个画出来会非常让你吃惊，这是让大部分人在大部分情况下犯错误的东西，所有指数型增长的东西在最后都会让你极其吃惊。如果某件东西是指数型增长，比方说我们有一个很大的体育场，你可以理解成一个巨大的容器，比方说看比赛，忽然下雨，下的是指数的雨，会出现什么情况？在几分钟之内就会被淹，而且水的量的97%以上会在最后一分钟出现。以十为底的指数，10的100次方很多物理学家把它拿来当做极限，这是我们事件的极限，不管你拿什么说事，不管衡量标准是什么，都不会超过这个数。这个东西叫Google，google的名字就是这样。
放围棋的下法有没有google大，肯定有，他是361的阶乘，比100的阶乘大得多，所以比10的100次方大。你必须要有库来算361的阶乘，因为这很大，我来试一下，是错误。指数型思维。
画一下曲线是这个样子，算这个复利，5%年利，有点高。多项式，这个非常重要，可以说从今天所有的课，多项式是一个很万能的东西，在计算机里面有一个规律是，不管你算什么东西，相当设法变成一种加法，多项式也是这样，不管函数张什么样子，我们把它变成多项式的样子。为什么多项式这个东西好，首先这个东西可以研究的很深入，它的性质你都非常了解了，另外就是如果是多项式的话，你总是可以微分的，你可以一直微分。然后我们看一下排列的形式，这其实是一个面了，一个曲面，他有两个变量，之所以引入这个y,是为了告诉大家写这个多项式有很多项，谁写在前面，谁写在后面，他有一定规则。这个化简，合并同类项，看一下就知道了，多项式你可以把它理解成在整个二维空间里的很多线，点就是数，点的加减或者乘除就对应算数运算，线的加减乘除也对应这一些算术运算。我们定义了多项式以后我们在多项式上可以去定义四则运算而且大家回想一下昨天学numpy的时候，numpy向量本质上就是特别强大的向量，我们注意到，这其实就是一个向量。

## 4

你可以设想一下其实这里很有意思的题目就是没有用向量来表达这个东西，3,0，-4,5后面这个可以表达成什么？2,3，-2,2，就是这样子，然后，上面写的东西就被简化成了这样一个玩意，就是，是吧，也是可以这样表示的，然后你隐掉了什么东西，比方说，三次方，二次方，一次方，零次方，是吧，你藏起来了这些东西，所以你看，我们把多项式的加减乘除就对应到向量的加减乘除上来，这也是一个可以研究的，很好的数学问题，我们昨天其实也有一点涉及向量的加，在线性代数里面会讲更多的这样的东西，所以，在这个世界里面我们想了解对应关系，我们用一个函数去表达，无论这个函数写成什么样的形式，总归我们要把它拆成这样的形式，总归我们要把它变成一个多项式，如果我们把它变成一个多项式，我们就可以再做这一步，就是这个样子，在做这一步下一步是什么？昨天我们还有一个很好玩的工具，就是我们就可以把它塞到0和1之间，然后我们就可以把很多东西都连起来，炒菜是吧？要不然没法互相加或减，多项式相减，其实跟加是一样的，只不过你把这个减号变成一个负的加号，这没什么特别的，多项式相乘，多项式相乘特别容易出错，就是，为什么特别容易出错呢？原因是，他确实会少很多项，多项式相乘也对应着向量运算，这个都会啊？我就不用讲了吧，一共要乘6次，多项式相除，这个除法是你会的，你看它4x里面包含2x. 6x^2也包含2x. 就像刚才那个样子，这是积吗。这是他俩的积，这个2x除以它，就这么除，你跟除法一样，试商，叫长除法，大家有没有印象，初中代数里面学过这个，这个，长除法，就是试，就是一开始，我们试，x应该可以然后把x乘上去，一减，算出来一个差，然后继续，再继续猜下一项，就是这样就除出来了，但这样就有一个问题，你看我们现在是，加减乘除都讲了，是吧？然后他是个非常对称的东西，我们在单点空间里面加减乘除有了，然后我们在整个曲线空间里面加减乘除也都有了，那么大家回想一下，就是，我们一开始讲numpy的时候我们有这样的例子，就是它并不是完全对称的，字符串也是一个容器嘛，这就引来一个很有意思的话题，我们怎么去学数学？然后因式分解这是多项式一个比较有意思的话积，他就是把一个多项式分成很多的鸡，就好像一个数，16，我们可以把它分解成2乘8,4乘4这样子，多项式也可以同样的干，我刚才讲了一个多项式，就是，如果你一开始接触数学的时候，从记数字开始，然后学这个四则远算，学这个分数，然后学这个方程学这个变量，然后开始做多项式，解方程，你差不多学了整整十年，就是，在你学数学的最初的十年里面，你只学了一点，就是我们刚才讲的，因为，数的加减乘除，就是多项式里面只有x的0次方，那刚才介绍的解方程组线性方程组之类的只有x的一次方，那我们学了10年的时间，只学了多项式的加减乘除，多项式的加减乘除可以概括整个高中前所有的数学，那么如果你能解出来加减乘除，那么所有问题都解了，也就是说，我们刚才刚刚go through的东西，就是一些比如你小学，初中上的所有东西，算来算去他都没有出这个，而你这么去表达这件事情，就是，我印象很深的就是他不是像我们这样写了一个公式，他是做了一个程序语言，他这个程序语言就是涉及的目的就是要处理这些向量，处理这些高维的东西，然后他有他这个程序语言的符号，就是一页纸，一页纸里面把所以的东西都概括了，就是你可以把这个10年的数学都压缩到折页纸上，很简单的公式，然后，我们看一下因式分解，就为什么要求因式分解，有的时候我们经常问我们搞这件事情用什么因式分解，这是干嘛？求根的目的就是我们这有个方程，我们想知道他的解是什么，然后，最粗暴的办法，我们画出来就知道了，画出来，交点就是解，原来就有这样的工具，所以就有很多奇怪的做法，现在想来只能解一部分的问题，不能解所有的问题，然后如果正好是平方差公式的话，我们就可以记住，这是一个平方和公式，因为你过去的数学都是线上的，我觉得你也可以换一种教法，你从一开始就从上往下讲，然后如果你能想通多项式，你就可以说，我现在缺一座桥梁，就是从多项式到任意函数形式，就是级数展开，微积分，你就可以发现亦可以一下就跳到大学本科的所有课程里，这就是数学很beautiful的地方，最大公因数，它说的是上面这个式子，都有3，都有x，都有y，这个就用眼睛看就能看出来，然后我又把3xy提出来，然后用系数，一样的套路。这个大家都知道，平方差公式。二次方程，如果能做因式分解，解已经有了，是吧，你把它分解了，它就是解，抛物线，这是刚才那个方程，画出来这个，我们口算的点，一个是1，一个是-2，画出来一个碗，抛物线画出来的形状，在后面的课里面也会提到，大家都有二次的线性都不够，非线性，我们再看看，梯度下降，这个是什么形状？大家想一想，倒着的碗，然后你把这个坐标轴画出来，为什么叫抛物线？有没有想过这个问题？为什么抛物线是二次？因为加速度是一个固定的值，比如说，就是因为这个，所以抛物线就是二次的，抛物线还有顶点，然后，这是他我们把它写成一个规则的形式ABC3项，我们可以用抛物线这样表示，这就是为什么我们要学numpy，他最擅长做这种，我们今天找所有的东西都可以把它用成这个样子，都可以用来进行计算，契合的非常好，大家看一看，大概是这个样子，我把这两个线，都画出来了，然后，画的做一下标记，这个紫色的线是它的对称线，就是中心线，那个顶点，起始点所在的x，然后，这蓝色线是坐标轴，大家可以看一下。然后这是解一个二次方程，这个大家都能记住吧，这个二次方程有一个硬解，就是你只要把这个公式带进去，你就能算出来一个解，那后面方程的解，是不是任意次方程都有解？都有这个公式？5次以上没有？不一定有，有人研究过这个，伽罗华，它研究过这个问题，解这个任意次方程，你看他努力的方向，就包括爱因斯坦，想把这些东西都统一起来，所有的都再拔高一个高度，把他们都用一个一致的东西来解释，用一个东西来解释就非常好，你看这个就不是一致的，这是整个世界里面的一个小角落，那你知道了，如果你一直在这个角落里面，也会生活的很好，这就是把解也画出来，其实大家看一看这个我们讲的一些什么东西，你其实已经会了，就比如说你已经知道是怎么一回事了，我画一个图你脑子里也能画出来，但如果你从未接触过这个东西，这些图还是非常有用的，但是你怎么画这些图？但是如果你拿手画的画，这个过程会非常的复杂，你要点点点，但如果有这样的工具，所以计算机可以帮助学任何学科，计算机可以帮助学数学，数学可以帮助学任何东西，所以计算机可以帮助学任何东西，推理没问题吧，只可以帮你学语文，这是一个很好的工具，然后再往下，这是一个函数的basic概念，就是大家都知道这是什么意思，这是程序里面函数的样子，然后我们可以画一画，这是画一个啥？好，再往下，这个函数其实最重要的一点并不是公式，最重要的一点是这个东西，定义域，你只要讲函数的话，你一定不能缺少定义域，即使是非常非常有名的数学家，他有时候也会算一些错误的，把定义域给搞混了，就有一些很有名的悖论。

## 5

有一些自相矛盾的结论，就是因为他没有把这个定义域给注意好，定义域给忽略掉了，现在有些很好的，也不是很高的数学，中学的数学，X的定义域是实数域，这个是不能等于0. 我们也可以简化x等于0和这个一样，不用写的这么麻烦，这个画出来就是这个样子，这个图形画起来挺难的，因为你要找一个合适的值域，你才能把这个图像要表达的这个点画出来，也就是说，在这一点函数其实是没有定义的，所以我们就专门画了一种这种，有个圈，然后其他的曲线，还是光滑的，我们可以看到，出现了很多特殊的状况，这些特殊状况就是在我们的机器学习，后面的课里面要注意的，就是这种特殊的状况会导致你的搞不下去了，你的这个点没法求导数啊之类的，这也是函数的形态，再举一个例子，这个函数我们是把它故意的，也不是故意的，在这个实数域里面，负数平方根没有定义，根号画出来是什么样子，画出来是这个样子的，这个点画了一个实心的意思就是说，0是可以的，0也是包含在这个定义域里面的，画一个这样的线，然后我们也可以人为的设定一些边界，像这个，就设定了0和5，我们就这样设，画出来就是一小段断线，这是阶梯函数，就是两段这样的线，其实是两个点，然后函数的值域，就是跟定义域对应的。这个点其实画的不是很好，因为这个坐标轴太大了，这是2000，你看上去他在0那里，其实这个焦点是在一那里，休息一下。然后给大家看一个好玩的东西。

## 6

开始，然后昨天我给大家看过这个东西，这个东西你学数学比较好，wolfram，有的时候你用sire搜什么东西它底层的search就是用它，然后，他不一定非得是数学，什么都可以，你可以试一下，什么东西都可以，然后他就computing，然后你看，这是一些factor，这是一个很大的图，比方说，我们可以点，这是他女儿，我们点，然后你又跳到另一个界面了，就是他是一个非常结构化的东西，你可以一直explorer下去，这是一个很好玩的东西，我们回到sin这边，就是，我快速的查一个公式，就是这个东西，看见了没，这个，不要被他吓到，你要是顺着写的话就非常有韵律，很有节奏，就是，这是一个多项式看出来了吗，这是一个多项式的求和，就是它是什么x的平方，四次方，的一直往下，底下是一个系数，底下是一个阶层的系数，然后，这个系数一个是正，一个是负，你可以想象一下写出来反正就是一个多项式，x的四次方我们就知道了，所以，就我上午说的我们讲一个课，从python开始，讲python是为了导入我们昨天用的那些库，numpy其实可以表示多项式，然后，这里有个sin，看起来和多项式是没有关系，我们也可以让他有关系，然后他也可以表现成一个多项式，你想想，我们可以把sin表示成一个向量，就这样子加就行了，然后，我们下面给大家演示了一个东西就是，这个世界上，很大一部分，函数很大一部分曲线，都可以搞成这个多项式，我只是这样说一句就有一些印象，但是你的印象不深很深，但是sin知道能变多项式，能用多项式就能用numpy算，然后我就可以用python来解决这个问题，来给大家看一个例子。其实我们上一节课，讲了初等的代数，讲了这个多项式的概念，多项式是干什么用的，我们肯定不是只是为了讲多项式，后面要用到它，但是今天给大家看一个神奇的用法。就是这个video，这个家伙它在youtube上订阅量很高，他在nasa工作的，就是，他喜欢高一些科学啊，做这种古怪的实验，然后这是他的一个采访，然后讲的是什么事情呢，讲的是傅里叶变换，大家知道吗，傅里叶变换就是把这个时序上的东西变成sin的和，他的basic idea就是所有的曲线就是你都可以用傅里叶变换做出来，昨天我们也提到了，他的说法就是如果你可以做傅里叶变换，傅里叶变换就是sin的正玄波，所以你刚才看到了一个轮子在spaning，你能不能build一个模型像我们刚才说的那样，你拿一个装置来模拟整个这件事，拿一个杆子，一个杆子头上又有一个杆子，然后你在那里转，你可以把任意曲线画出来，这是可行的吗，然后。你看，那个时候他上大学老师给他出了个题，你要画出来这个东西，中间还有一个拐点，它就是用计算机做了最后一件事，他有一个程序，然后做之前他推导了很多公式，所以有一些手写的东西，其实这些学东西的形式，今天我们也是一样的，看了一个公式，然后，然后把这个公式输到Jupyter里面，可能我们现在不用打印出来一个小纸，我们在这里面直接画出来了，就是他当时的想法，然后，他做了一个动画，你看到。这个意思怎么去理解这件事，每当他加法的一个结果，这个加法就相当于我们昨天做的那个accumulate，就是他是一个累加，它先是有个3，然后又有一个三，然后他两加起来以后，就不再是这个样子但还能看出来，然后你越加，越趋近于它想画出来的样子，这就是他这个东西的源头，他是一个数学家，然后看看他怎么搞得，你注意到它这两个转的速度不一样，就是它的sin的频率不一样，然后它长度也不一样，就是长度不一样，它前面的系数也不一样，然后你就把它们加起来，你看他把一个正弦波搞的已经有一点像方波了，他的目的就是把一个正弦波完全搞成一个方波，你可以想象加加加加加，它达到这个目的，它99个基本就是方波的现状，它其实就是做了一个傅里叶变换，你的傅里叶变换其实就已经有sin的值了，再把它分成不同的频谱，把方波拆成一个sin的series，就相当于方波也是一个时间序列，然后你看他的频率，他用的就是wolfram，他说我给你一个特复杂的东西，任意曲线你行吗？然后你会发现他没有任何的迟疑，因为这个在数学上是可以证明的，如果这个东西在数学上可以证明，他只是会做错而已，他总归能做出来的，你开始会做错，这有4个曲线，你要错4组，你要画出来，他的第1步是什么？他的第1步就是顺着这个曲线走，他把xy的点取下来，就是他要先取得这个曲线的表达式，最简单的办法就是把它搞成一个函数列表，我们说刚才的函数形式，一个列表，一个公式，或者是一个图形，这是第1个版本，画出来是这个样子的，完全看不出来是什么。

## 7

这个过程就很像我们做machine learnning后面的，一开始其实你的build logic非常简单，里面就是一个激活函数，你用这些东西组合出来一个曲线的一个规律，然后你一步一步的迭代去接近她，然后你一步一步的迭代去接近她，如果这个东西是可以被你探索出来的话，你最终能画出来一个非常像的东西。看差不多在80的迭代的时候，就已经非常接近他想画的这个曲线了，这个也像我们做探索的时候，你的training，它不是无限的下去，你再train下去就没有任何含义了，你怎么知道我已经足够接近了？或者我这个东西是试不出来的，很快你就可以得到一个结论，别看他这个数学，多项式不起眼，它其实做了很多事情的。休息一下吃个午饭。

## 8

今天下午讲微积分，然后有时间大家布置一下作业，有同学反应对于git不是很熟，我们作业也是用git让大家去做的。这节课讲微积分，微积分还是挺有用的，我们从极限开始，先讲变化率，rate of change，这里有些符号大家约定俗成的，其实我们在算斜率的时候有这四个东西，下面给了个函数的例子，画出图形来，那个紫色的线相当于我们在算变化率，大家看到这个比较大的跨度，如果我们把这个跨度缩小的话，就会像这样。极限，比方x^2+x求在x=5的这一点是多少，现在看到的这个图就以前看到的不太一样，这里有几个工具，这个是移动，下面这个是放大，所为极限就是，比方说我们把fields拉大一点给大家看一看，x=5的这一块，当我们越来越接近于这个点的时候，你能算出来这个值，其实他是个固定的，代进去，不一定大家都能构出来，大家看我的就可以了。然后我这儿又有一个函数，这个函数比较特殊，刚才我们也讲到了这个函数，x不等于0，中间有个洞。大家注意看，这也是一个不连续的函数，这个函数我们刚刚也看了，我们现在把这重新画出来，他们斜率是一样的，一个点是实心的，一个点是空心的。然后再举一个例子当x趋近于25的时候，分母会变成越来越接近于0，那我们想知道趋近于25的时候是这个function会是怎么样的，画出来是这个图形，你注意看下这个坐标轴，0在这里，这是25，他会无限贴近于这个线，在这两边都会接近正无穷和负无穷，这是这个图形画出来的样子，这叫什么，这叫双曲线。然后他的数学公式，你看，就是这样来表达的，仔细看下面写着25+表示从右边趋近和我们从左边趋近，右边趋近是正无穷，左边趋近是负无穷，这些概念比方说无穷，极限，然后变化率都是非常简单的，平时是很容易理解的，但是如给他一个非常正式的数学证明的话，你会发现这非常的麻烦很啰嗦，因为极限的数学定义是一个很啰嗦的东西，我们在这里不搞这个定义了，往下走。然后这个函数，比较有意思，x=0定义了一个值，除了这个点，他是一个像抛物线一样的东西，这个东西画出来给大家看一看，然后我现在问题是x在0这个地方的极限，他是5因为正好有个定义了，他在x=0上是1，你看这个图形就能明白理解了，他会无限趋近于1，但他的定义是5，极限跟函数的定义还是不一样，有的时候你能把他代进去做，有的时候你要理解他在物理世界是什么含义，这是极限的概念。
然后同样的我们也可以求地方说类似的x趋近于1的时候，它的极限是多少，你把1代进去你会发现上面是1，下面也是1，你把上面展开之后用平方差公式跟底下消掉了。如果我们把他画出来，应该是一个直线，同样的办法，我们也可以用多项式里面学到的东西做一个类似的，对于x-4对于根号下x加2，x-2，然后根号x-2被消掉了，我们可以把4代进去，答案是1/4。极限的算术运算，这个地方有点不太对，我们没有fix一个bug,这个地方下标怎么被layout这个地方了，谁能找到方法。我特别喜欢这个公式，公示一看不用记，很整齐，跟你猜的一样，跟你的直觉是符合的，和的极限是极限的和，差的极限是极限的差，没有什么特殊的地方需要记录他。大家有没有什么需要停一下的，不明白的地方，应该都学过微积分吧。
微分和倒数的定义，导函数的定义就是这个样子的，给他一个微小的量h，然后让h趋近于0，然后这时候它的极限叫导函数，一会儿我们课程会用这个公式，我们做多项式导数的推导会用这个公式，你会发现讲课也好，这些数学概念之间其实是连着的，前一个概念会决定你后一个概念，然后没有前一个概念，你也没法继续往下进行，这看起来没什么意思。这是另外一种记法，你可以记成h趋近于0，是等价的。然后我们根据它的定义，我们应用一下。这个比较长，就是把刚才那个二次曲线，把这个，求2就把2放进去，然后我们就把这个公式带进去x^2+x,化简以后在继续往下算，最后算出来这个。其实就是走一遍这个公式，我觉得数学这个地方就更容易分类，数学这些公式，我们大家随手拿，就能画一画，因为我觉得，数学最好的工具，最容易教的环境，只有纸和笔，你看andrew 在coursera上的课，他很多时候就拿一个粉笔在黑板上推导公式，为什么其他形式不行呢，因为你看不到过程，如果他不是黑板和粉笔，只要是纸和笔，你可以一步一步看到过程都可以，自己要动手写一写，这样有好处。你写这个公式然后你的思维要习惯这种符号表达，我可以给你们看一下我的笔记。

## 9

你一定要很仔细layout你的笔记，都是手画的，你公式都是画出来的。导数的几何含义，画一个切线，数学上就是这个含义，然后光滑也有一个数学定义的，可以处处可导。导函数不明思议求出来要是一个函数，刚才那些东西都带到那些极限，导数的定义里面，然后跑一遍极限运算，刚才我们也学了极限运算，这是我们今天最重要的结论，就是x^2+x,如果我们给他求导的话，规则就是指数放到前面然后减一，然后依次类推，这个很容易记住。这是一个概念，这个概念我们在后面会用到，我们所有的优化也好，machine learning的几何函数去算，一定有这种形式的，如果没这种形式我们得不到这个结果，什么叫可微，概念就是连续可导，不能有洞，然后光滑，还有就是切线是竖直，如果切线是竖直那就意味着我们导数是无穷，我们只看画出来的样子，所以如果你们有兴趣自己做一些实验，其实一个简单的办法就是这两页里面有大量的code，你找一段贴上去改一改，然后看看图形上会有什么变化，大概就是这个样子。求导规则，这也是非常重要的一个点，我们先把他列出来，常数的规则，比方说我们一个数求导，两个函数的和求导就等于导函数的和，差也是一样的，然后就是幂规则，这个都是基础，就是你可以说我们记不住这么多导数公式，但这个你必须得记住，只记住这个，百分之六七十的情况你都可以cover，然后我们把这个规则推导一下，我们现在唯一定义过的东西就是什么叫导数，这是我们第五次用这个定义了，所以你也可以做个证明。这个乘法规则，这个可能比较有用，但我觉得这个例子不是很好，但是乘法规则还是大家必须要记住的，两个函数的积等于其中一个函数的导函数乘以另外一个函数加上另一个函数乘以另外一个函数的导函数，大概这个样子，这跟刚才那个极限的定义不一样，如果你记不住可以验证一下，因为你已经知道这种函数的求到了，然后你说把这两个乘起来，你把他做一个多项式乘，求出来另一个多项式然后利用幂规则或者乘法规则，最后得出来结果应该一样，如果一时想不起来你就举一个简单的例子，一试你就知道了。你知道这是有规则的，用这个运算来搞出来，我们也很少用的。链式规则，这是函数的函数，他其实是在求导数的推导的时候仅次于米的规则，因为幂的规则，但是如何去分解函数所谓链式，这个写法他的意思是一层函数，然后再来一层函数，你可以一直这样阔起来，这种东西在函数编程里有专门的名字，你可以运用一串函数，比方你做一个音响的系统，你要处理声音信号，你有很多滤波器，放大器在中间把他们连起来。我们用一个例子来研究机制和优化，我也只是把这个规则列了一下，大家也可以再看一看，记一记，大家以后去哪儿找这种规则。
看下面这个图，这个绿线是函数，他是一个二次曲线，你脑子里面想一下，二次曲线的倒数是什么啊？应该是直线。这是某一个点上导数的值，你可以看到这个斜率是他的值，所以你看这个曲线虽然是抛物线，但他导数的函数画出来是一个直线，这说明什么啊，如果对应到物理现象，连续求两次导。找最大值和最小值，方法其实在上面那个图里面已经显示出来了，你看，距离地面最远的那个点在这出现，他就是极值，在这一点速度为零，他的导函数跟x轴的交点，求出来x的位置就是他极值的位置，他运动的时候你想象一下，他的距离在时间轴上画出来以后，然后我们就用这种方法，我们求它的导数，算截距。举一个具体的例子，这个函数也是一个抛物线，只不过跟刚才一样，这是最低点在-1，他的导函数的值是0，跟我们刚才的结论是一样的，我们找到了极值点在哪里。下面来个复杂点的抛物线，是S型的，他是三次的话，他的导函数就变成一个抛物线了，三次曲线求导数就是x方，他对应的这个点叫做拐点。然后回想一下刚才的我们用的方法找极值点，如果这个曲线很复杂，不是简单的抛物线，你就可以想象，它是一个波浪，波浪会有很多极值点，但是这些波浪可以不一样大我们上午看了一个方波，一开始模拟的时候有的地方高，有的地方低，所以这个结论是很明显的，极值点不一定是最大最小值，他只是区域里面的最大最小值，然后就开始举例子了，我们能找出这个点来，但他不是最大值也不是最小值。我们通过二阶导数这个符号，通过刚才那些例子我们总结出来一个算法，怎么去找极值点，，先找一个导数，然后让导数等于0，等于0的时候应该是个·极值点，然后他是不是最大值呢，你可以再求二阶导数，然后通过球二阶导数可以检验他是不是最大值。是最大值会是什么？二阶导数也是0，然后偏微分，这个就是大家说的考试的时候，偏微分有另外一个变量，他不是在一个曲线上，是在一个曲面上，然后偏微分的意思就是你只对一个变量的变化做微分。

## 10

这里有一个概念就是，这个概念叫梯度，梯度后面会讲，就是，后面的课会反复提到这个梯度和梯度下降这些概念，在这里给他一个数学上的定义，比如说，刚才算的这个区间，我觉得如果你不给一个值的话，就应该你的定义域也会出来的，这个圆锥面，这个是梯度的公式，我们给一个。这个图我契合画的不是很满意，你大概知道它想表达什么意思吧，它这个箭头的大小是这个值的大小，然后，你可以把它想象成一个从一个碗的上面往碗的里面看，看了很多线的样子，然后，这个东西应该画出一个三维的，我还没来得急改这个，画一个三维的比较cool，看起来可以操作的，物体object，下次上课的时候我再更新一下，这有一个说明，昨天我们也提到了类似的梯度下降的算法，这就是一个算法的一个表述，从一个点开始，作为一个起始点，然后，计算梯度就是刚才算的偏微分，算出来以后，然后，就可以算出发现，沿着这个方向再往前都一步，然后再算，然后大家就可以提出一个问题来就是说我们有个走多远，或者说，我探索的步骤是什么，其实，这个问题不用担心，因为，在数学上，你越接近他，你探索的就越密，你一开始你会下降的非常快，就好像，可以画一个图，我们随便找一个点，假设我们想趋近的目标在这里，我们起始点在这里，然后这是画了一个切线，然后，我们从这边再做一个切线，你上面会找到一个交点，这是第一步，然后，找到第二个，这叫沿着梯度的方向前进，这叫前进一步，然后找到这一步以后，我们又可以画一个切线，然后再往上长，第三步就是它，第三部以后，在这里是吧，你看，他不是均匀的，它很快的就过去了，然后，但是，离这个目标点越近，他就越密，越细，因为它开始变得平缓了，然后你就不会错过这个点，这就是这个算法的好处，他在数学上有这种性质，做梯度下降的时候你说，我应该设什么，你不用考虑这件事情，你只要往下求导，很快就过去了，这个大家可以放心，这个谁想出来的，对，牛顿。但是牛顿确实是个影响力很大的人，我们经常能看到他， 反复出现的，到现在我们还在用它的东西，而且他的做法有点像我们这个领域，我们这些领域有一些硬来的做法，比方说如果你不知道一个解，你就暴力破解去算，使用蛮力，在他这个年代也有一些工程原型，大家开始都对天体感兴趣，因为你肯定要build一个大望远镜去看天体。下面开始进入牛顿的领域，积分，有人好像在和他争这个东西的发明权，无所谓了，然后我觉得这个积分的东西用手练一练，我们今天讲了一整天大家也没动手，我们也没有写任何代码，一会儿课结束时，我们来写一下这些积分，积分就是微分的逆运算，所以你能求微分反过来就能求积分，就是这样子像这个，我们想一想它积出来是二分之一x的平方，它应该是什么，我们能猜出来是吧，你积分的结果再把他求导数，你就能退出了fx是什么？像这个其实就能猜出来，对，就是这个极限。这个，它的几何含义，我们说了，求面积，写出来了，等于x。好，怎么算，这个什么我们必须用这个库了，我们用了很多numpy，这是我们第一次用这个scipy，就是，你看，我们用这个，上节课的时候我们做的这个，举证求幂，我这有个举证，我要求幂，我不知道怎么算，我让这个来算，这也是我们另外一个，积分，算积分，一般的计算器可能就做不了积分，手机上，电脑上有的可以，科学计算机有的时候带积分的，想这个，我们可以算一算，算出一个积，首先是这个参数，首先是被积函数，被积函数我们是先写了一个lambda，刚才那个fx已经被我们给定义过了。这个是参数，然后这个是返回值，这个就相当于是fx，反正那个地方写上一个函数名就可以了，这个是积分的起始点和终止点，就是这个东西，你看我画的，这是这个，你可以认为是它的面积，这个黄的东西面积是多少？正好是2，还再来算一个积分，这就可以用到我们刚才学过的这个公式，刚才求导是这个方向x的三次方，把3放上来，这里是2，做积分的时候就反过来就可以了，一样的，这脑子转一转，我们就要少算一下，用纸算一下，不要太懒了，自己手算一遍，最后你要算出这个数来。脑子想一想也行。

## 11

这是再高阶的，3x方加2x就上面这个，大家刚才算的这个。做一下积分，画一下图，就刚才有同学问，这是啥，就返回2个值，你查一下这个文档，abs error就是，求这个，这个其实很好做，因为我刚才已经告诉你们了，ex方求积分，我们来做一下，就直接算，下面做一个比较有意思的，这个。我把这个公式写在这里，我们今天做这个积分的最后一个题，然后这个公式它是高斯分布的概率密度函数。概率密度什么意思，就是说当你的分布的不是离散的时候，就是，你可以把它想象成概率平均分配在0到1之间，然后，我们给他起了个名字叫然后，在这个，中心曲线上面去做积分的话，你根据这个定义，大家其实可以想一想就是这个最后做出来的值，应该是1，我们可以先算一下，差不多是1.你看他其实给出来的是这个下面会有些误差，然后，我们手来算一下，上面这个例子，这个定义在这，我们来搜一下网络上的定义，高斯。公式和我们不太一样，注意一下。他这公式是一个，我们那个东西其实是一个把期望拉倒0，然后方差相当于往上增，这个u是0，所以这个没有拉，这个也没有拉，这个2拉了，这个就变成了x方，所以，跟我们这个还是一样的。就是这个公式我们写在这里。这个，在微积分里面，我们通常写一个x，但是在一个概率统计里面，我不知道为什么就是z。他不会写x，它会写z，我们要follow这个习惯。然后来算这个东西的微积分，这个其实你看上去你会挺难积分，因为你知道它，这个好算，但现在不是这样的，现在是这样子的东西，就是这个周末算，然后，这里no ieda，不知道要怎么搞，然后，我们手算一下，要不然我们整堂课一个都没有搞过。这个基本想法挺有意思的。我们来分析一下这个东西就是我们做一个求导数的常数是可以不用理他的。就比方说我们可以把这一项拷出来，我们先不用理他，你写一个这样的东西，我们来简化它他就会变成了一个一，我们还是先回到x，就是，本质上我们是要求这个东西的积分，然后，有人就想，这个积分，不会啊，这样子搞，再乘以他这个想法看起来非常stupid，救你本来就搞不出来，你再乘，你能搞出来吗？但是这里是正好，你能搞出来的，你看起来不靠谱的瞎弄就行了，我改一下，我写x的话我其实也可以改y，我可以把它改成y，是吧，我不要写x，我写成y。但是一样的，如果他是一样的话，你发现这不是二重积分嘛，对吧，所以我就可以再继续写，把它写成一个二重积分，这里到这里，可以这样写吧，dx，dy。这个就是看起来好多了，最好能产生些联想，这里，x方加y方我们也测过，园嘛，我就想着画一条坐标系，现在在坐标系上，画到积坐标系上。然后，如果我们画一个很小的范围，比方说，我们在这个二次曲线的，这是x，这是y，然后我们花一些格子，x1，x2，y1，y2，大家看这一小段，这个东西我们叫什么？dx是吧。这个叫dy，dx乘以dy就是一小块面积，就是这一项，类似的，我们把它变成一个极坐标系会变成什么样子呢，极坐标系是有这个。画一个这样的，就是一个是离原点的距离，一个是角度，应该这样的图，不同的角度，这个是半径，我们看这一小片。这叫dr，这是什么？这是rdsita。好也就是说，dr乘以rd也是一小片面积，和这个是一样的。然后这是r方。前面，因为你xy是无限大，你们对于角度来说真个2pi，所以我们就写0到2pi，这就到了最关键的一步，变化，到这里，这个东西我们很喜欢。他是什么，他其实我们放大了看的话它其实是，是不是啊，跟他是一样，所以我们可以做一个快速的变化，这个推导你是看懂了。然后我们就来算他，算他其实非常好酸，因为我们知道。我们最终搞出来一个我们熟悉的东西来，用这个好方法，你看这个东西，他最后算出来应该是多少，1是1吗，这东西算出来是1，如果这东西算出来是1后面的也没有必要算了，后面算出来就是2批，最后的结果就是2pi，但不要忘了我们一开始是乘了一个东西，所以，我们这个东西，1/2，写一个这个东西。是吧，然后带进去做个结果应该是1，这个很明显，正好2个都消掉了，对吧，跟最后算出来的结果也是一样的，就是说，我们验证了一个概率的我们沿着概率密度去做积分，然后提出来整个概率的和应该是1，所有事件加起来的概率是1，跟这个算出来的是一样的，很好。下面再给大家看一个东西，你看pi都出现了，我找了一个和上午话题有点相关但不是我讲过的这个pi，是另一个pi，给大家看一看，也是一个video。就这是结论，它想讲这个。然后，这有些神奇，你把这个数字平方最后加出来是这个，怎么来解释这件事情，数学上你可以去算，去证明，上个例子我们解释傅里叶变换的例子我们其实是做了一个屋里模型，看了小棍子甩，我们还刚才讲了一个比较简单的例子，抛物线，这也是一个物理的例子，你不是那么容易想到的，很多时候你解决问题最难的部分是你不知道从何开始想起，还有不知道从哪里想出来的。

