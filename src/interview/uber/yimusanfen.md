这周刚结束的Onsite, Uber的面经一直都挺少的, 所以发一下帮助有需要的人 :) 我是通过内推拿到面试的, 流程就是很简单的: 电面 -> Onsite -> Offer! 另外平时主要写Java和JavaScript, 所以是用Java面的. 电面: 一开始对方先简单的介绍自己, 然后轮到我简单的介绍自己, 接着挑了一个自己的项目介绍. 紧接着是算法. 对方先出了一道题, 问我见过没有. 我表示我见过… (Word break LC原题) 于是对方又换了一道题 (Reverse Words in a String II 还是LC原题). 但是这次就没有问我做过没有了, 简单讲解思路后麻利的写完, 并且写了简单的case测试. 途中也讨论了特殊情况并且印证结果 (比如leading & trailing space的处理). Follow up是加入符号但是reverse的时候需要保留位置. 我大概讲了一下想到的两种思路, 不是最优, 并且由于时间不够, 也没有写完. 面试官最后提了一下最优思路(用Double Stack)并且让我问了几个问题后就结束了. 大概不到一个小时后收到邮件表示可以move on. Onsite: 第1轮: OO Design. 设计Excel. 本身不难外加面经见到过, 所以准备充足. 现场手提接上投影直接在IDE里面code, 用IntelliJ那叫一个爽快 :) 结束后对方还问了我一些关于Java的问题. 第2轮: System Design. 设计Instagram. 全程对话, 基本就是画图解释回答问题. 由于准备有好好地准备这一块, 所以基本还是能流畅的进行. 虽然总体感觉一般般. 第3轮: Project & Algorithm. 先是展示自己的Project, 现场我也是直接打开IDE来展示Code, 解释主要的Component, 并且回答疑问. 接着在白板上做了一个简单的算法题: 给一个linked list, 返回一个reversed copy, 原来的不能改变. 我先写了一个用Stack的简单解法, 然后对方要求再来一个O(1)空间的, 思考一小会后就解释一下思路并且写了code. 写完后提示有bug, 检查发现后改掉了. 最后要求整洁代码, 又被提示有个小bug, 囧… 在提示下改了. 第4轮: All kinds! 先简单展示自己的一个Project, 然后问了一些Javascript和Java语言特性的问题(顺道写了一个Singlinton的例子). 接着问了一个判断Palindrome的题, 讲了各种解法后写了一个双指针的代码, 然后又问了一个关于Binary Search的算法题. 最后是一些传统的Behavior questions. 前三轮都是Engineer, 最后一轮是Team Manager. 总体感觉, 每个人都很Nice, 包括前后两个Recruiter, 所以现场一点压力和紧张感都没有. 而且还有最喜欢的伊藤园茶免费喝…. 难度的话, 仅就算法来说的话并不算太难. 但是考察的还是相当全面的, 并且感觉Behavior question也很重要. 所以是有必要好好的准备一下的. 不得不说的是, Uber的效率的确很高, 两天后就收到了Offer. 也总算可以喘口气了. 最后祝愿大家都能拿到Dream Offer :) 

链接: https://instant.1point3acres.com/thread/126383
来源: 一亩三分地

补充内容 (2016-3-27 15:35):
Phone Screen Follow Up Example:. more info on 1point3acres.com
"This, is a - test" -> "test, a is - This"






www.multreg.xyz/bbs/thread-193460-1-1.html



Uber店面.. 1point3acres.com/bbs
问了什么是RPC, 怎么实现的. Linux的file system的结构, 最后让我自己设计一个结构可以存很大的file.
接下来是算法题: 有一个很长的list<pair<int, int> > 第一个int 的这个node的序号，第二个int 是这个node 的weight。 写一个函数返回node的序号， 比如：
(2, 3)->(3, 5)->(1, 7). 那么返回2的概率是（3／15）， 3的概率是：（5／15），1 的概率

. 涓€浜�-涓夊垎-鍦帮紝鐙鍙戝竷
补充内容 (2015-9-4 13:12):
算法题，我后来琢磨了一下：
Basically divide the input list into two parts.

weight = (weithtUntilNow + thisNode.weight), so generate a random number, randWeight = [1, weight]. if this randWeight > ...









