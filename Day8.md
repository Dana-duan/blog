记录计算机小白学习编程第八天的感受。

在分享之前，一定要夸夸前几天在**Typora 设置的自动保存**小技巧。

昨天晚上，我编辑完信息后直接复制上传，之后就把电脑关了。今天晚上回来打开电脑，却发现昨天的文件没保存，文件夹里也找不到，当时我有点慌。

但是，我想起前两天设置过自动保存，于是赶紧回到设置自动保存的偏好设置位置，那里有个“恢复未保存的草稿”选项。我点进去一看，哇塞，里面有好多历史记录，我赶忙把昨天的文件保存了下来。这真的是个非常棒的习惯，在此分享给大家。

接下来再聊聊另一个又打破我传统认知的经验感受。

昨天我分享的内容是关于标签元素和基础架构的，今天继续往下学习时，又有新发现，知识就像层层堆叠的积木，不断积累，越学习越觉得，学海无涯，人不能给自己设限呀，我以为的不是以为的。

但是，还有另外一个我理解上的有比较大的不同点跟大家分享下！

还是依旧感慨，大佬实在是厉害！今天学习前，大佬给我发消息，提醒我跳过涉及样式的板块。起初，我以为有一个专门讲解样式的独立板块。然而在学习过程中我才发现，无论是插入图片、超链接，还是设置标题标签、文本标签，每一个细节都涉及到 样式的概念。这可太颠覆我的认知了！我原本以为跳过的是一个大板块，没想到**这些内容本来如同人体的骨骼、血液、组织，脑神经一样，与各个部分紧密相连，人体在每一个动作的时候，所有的版块基本都会涉及**。（最近经常举这个例子也是因为在学习费登奎斯的课程，就是有超级大的收获。当自己对一个动作的意向清楚的话，那动作就会改善。对于我来说就是脑袋里面有了一个self image 之后，身体的习惯动作自然就改变了。真的神奇的很）

**所以我也是发现自己很多时候，只是从字面上理解一个概念，并不是真正的理解。所以我特别想说，学习一定要基于自身的真实体验感受，否则学了也容易很快忘记。**

接下来的学习，我们先引入官方文档的概念。前两天以及昨天的文章开头都提到过<!DOCTYPE html >，这个是官方文档（相当于还是要给浏览器定义这个是什么文件）。

**这里有个小问题留给大家：HTML 元素和 html 元素是一回事吗？**

前两天我分享自己琢磨的任务时，提到设置语言的<“html lang =“zh-CN”>，在 html 元素里。它有两个功能：一是帮助语音合成工具确定发音，比如我们看公众号文章，上面的“听”功能，网页工具要确定用中文、粤语还是英文发音；二是为翻译工具提供翻译规则。

### "如何在 HTML 中插入图片和链接?" 

接下来给大家今天分享一个看似简单的话题——如何在 HTML 中插入图片和链接。学完这部分，我着实有点懵。为啥呢？图片和超级链接在日常生活中很常见，看似简单，但涉及好多基础知识呀（学习任务已加载完，明天候机的时候再好好理解一遍）

关于图片和超级链接的知识，原来这里面细分很多项，有些属性是必需的，有些则是非必需的。 在非必要的过程中，它为我们带来了哪些便利呢？

如何插入图片：图片能够呈现图像，所以就比较好理解，在 HTML 中插入图片时，要使用 img 元素。

这里有两个常见的元素属性，一个是 src 属性，这是必需的，因为我们必须明确图片的获取来源，用专业术语来说，就是文件路径。

另一个是 alt 属性，它虽不是强制的，但有两个重要作用。我在探索过程中发现，当图片加载失败时，它会给出提示，比如显示“图片资源没有加载出来”这样的文字，或者出现一个小图标。

另外，与我们最开始介绍文章提到的设置语言功能相关，这个属性会让屏幕阅读器将图片描述读给那些不方便看文字的使用者听。例如盲人朋友，他们看不见图片，却能通过听图片描述来了解其含义 。 

那么，该如何插入图片呢？首先要用标签表明操作意图，使用“img”标签后，从服务器寻找对应的图片资源。资源来源多样，包括本地图片和网络图片等等。

同理，插入链接需使用对应的“a”元素。“a”元素的英文全称是“anchor”，意为通过链接找到目标内容。它有两个常见属性，其一为“href”，是“hypertext references”的缩写，类似“引用长文本”之意，该属性需填入URL地址，如网址或本地地址。另一个属性是“target”，明确用何种方式打开目标内容。

**相当于是每个单独的标签，里面用不同的属性将我们想要的内容以我们想要的方式呈现出来。**

以上就是我今天所学内容，分享给大家。伙伴们，明天见，愿我们每天都能进步一点！

**内在os**：最开始的时候，我觉得就是15个问题，还没开始学习之前，我觉得很简单，一两天搞定。现在来看，一天搞定2个问题都是很厉害的。但是或许也会跟最开始学习常用命令行的时候一样，基础概念搞不清楚，就是操作不了。但是一旦弄清楚熟悉之后，就会发现很顺利的使用。加油呀，天天给自己加油的Dana同学。