# WFH，远程团队如何找回办公室的协作感


#### TL;DR

> 在雪崩之下，没有一片雪花是无辜的。

在这1个多月期间，我所在的团队体验了一段美妙的远程工作时光。
虽然我们的项目上有着50多位同事，多个小团队并行工作，
但是我们的团队依然保证和WFH前的交付速率和质量，也没有为了保证速率而加班。



回顾团队在这段时间的点滴，我发现如果远程团队找到办公室内的协作感，就可以降低协作成本，提升团队的交付效能。

我从团队的实践中提炼了以下几点：

* 围绕 Slack 这样的即时协作平台构建一个线上交流空间
* 举办短促频繁高效的站会给团队在一起工作的感觉
* 使用固定的视频会议室来缩短天各一方的空间障碍
* 通过电子可视化恢复团队协作的物理感
* 使用日历/提醒来提高勾搭协作的成功率



### Long Version

我希望我总结的实践集合：

> 为了  *远程软件开发团队*
>
> 他们在 WFH 期间发现团队沟通成本直线提高，导致项目的交付周期变慢，质量变差
>
> 这个：*团队协作速效救心丸*
>
> 是一个帮助团队迅速找回在办公室协作模式的药方
>
> 它可以为转入远程工作模式下的团队提供一组非办公室内协作环境差异列表，以及一组建议帮助团队尽快找回办公室的协作感
>
> 而不像另外一些远程协作建议那样，需要团队花大量的时间优化工作任务的组织分配、提高工作人员的协作能力
>
> 我们的产品：可以在1周内快速帮助团队降低协作成本



###  具体的实践

##### 围绕 Slack 这样的即使协作平台构建一个线上交流空间

###### 场景：
团队在办公室的空间，作为工作空间的同时，也是一个交流空间。团队工作所需要的信息无时无刻不在这个空间中流动，这种信息流动推动了工作的顺利实施。

在 WFH 的时候，个人的办公环境只是一个工作空间，线下的交流空间荡然无存：

所以在转入远程工作的时候，第一件事就是构建一个线上办公室，让团队的信息重新流动起来。

###### 方案:

在这里，我推荐使用 Slack 作为构建线上办公室的平台。

在一个多月的实践过程中，我发现相比微信等即时通讯工具，Slack不只提供了群体对话的能力，也很好还原了人在办公室跟信息互动的体验。

让我们回忆下，我们身处办公室这样一个交流空间的感觉：

* 各种关于工作的信息都会流淌在这个空间里
* 我们可以只关注自己团队的话题，也可以选择加入到其他团队的讨论中
* 团队内会并行讨论很多话题，话题间互不干扰，我们可以在团队内多个话题间快速切换
* 我们可以有选择的 follow 一个话题，参与到其中，聆听确认发表更正自己的观点
* 我们会自行屏蔽当下认为无关的讨论，专注于手头的工作
* 我们也可以通过回忆的方式回溯参与的/周边的特定话题的信息
* 我们可以通过复述的方式将信息分享给后加入的同事
* 我们可以通过表情等多种方式表达想法

微信 这类很流行的即时通讯工具，可以很好的满足第一，二条，让信息流动起来和信息的分组。但是作为线上会议室，微信没有很好地提供信息的屏蔽和并行能力，海量的交互信息会使得每个办公群跟一个菜市场一样的吵杂。

在Slack里，

* space， channel， thread 三级可以重现人在办公空间对信息的筛选和专注能力；

* 历史信息的记录和搜索，可以实现人在办公空间内对信息的回溯和追踪能力：

在日常时候，我们可以这样实践：

* 首先可以建立一个项目空间，保证项目里的同事可以分享/专注于这个项目的信息；
* 在每个项目空间中，我们可以创建 channel 作为不同团队的空间，这个感觉就好像在办公室时候，自己团队附近的信息主要是关于这个团队的工作的
* Slack 还提供了一个非常有意思的功能 thread；通过 thread 可以针对 channel 里的某一句话发起一个专题讨论，可以被所有人浏览，但是只会通知给参与 thread 的人。任何关于这个话题的讨论，都可以不断被追加到这个 thread里来，构成一个完整的讨论上下文
* Slack 里的历史信息是不会被删除，并且可以被搜索的；任意一个新加入项目空间/channel或者新加入讨论的同事，通过浏览记录就可以快速回溯话题的上下文；我个人习惯会在下班前10分钟，浏览团队频道、项目公共频道今天讨论的主题，补充因为在家工作，失去的团队上下文
* Slack 提供了除文字以外的大量表情作为一句话的comments，显示在这句话的下面，代替面对面的表情来传递对这句话的态度

当然 Slack 提供了强大的自动化能力，这个在后续中会提到。



##### 举办短促频繁高效的站会给团队聚集在一起工作的感觉

###### 场景：

办公室不只是一个团队的工作空间和交流空间，同时也是团队的聚集空间。

在这个聚集空间中，团队成员享受共同的工作节奏（站会、午休、下午茶、下班）和随时获取到同事的工作状态。

而 WFH 时候，带给我们更独立的工作空间的同时，也剥夺了我们聚集在一起工作的感觉。
虽然我们通过 slack 建立了一个线上交流空间，但是当我们需要协作的时候，
因为缺少了共享的工作节奏/状态信息，会发现不知道网络另外一头的同事正在做什么，不确定对方是否有时间和我协作；不知道其他参加者当前的状态是什么，判断不了发起一个多方协作的合适时间。

团队也不知道是否有人遇到了困难，谁可以帮助他。

###### 解决方案：

通过每天组织2-3次的线上站会，重新创建一个团队的聚集空间：

* 所有人 all ready 的一个信号
* 通过经典三句话 ”已经做过的事情，将要做的事情，提出困难和风险“ 来共享自己的状态
* 提出自己的协作需求，例如：我下午需要找 BA QA 一起完成 Story 的Desk Check并约定时间
* 响应团队成员的协作需求或者提出自己的建议
* 发布团队级别的消息

在 WFH 的站会需要参与者提前做一些准备：

* 在站会前确认自己是否需要协作，什么时候需要协作
* 在站会前尝试描述清楚自己的协作问题是什么，保证请求更加清晰找到对的人，例如：我到底是不知道这个问题该怎么解决；还是不知道这个问题的优先级是什么，是否可以延后解决？
* 尽量将站会后1个小时内的时间空出来，经验表明站会后立刻开始讨论/协作的成效是最高的
* 提醒自己站会时候要更加关注需要解决什么问题，确定相关人员，而不是问题的解决方案，因为一旦深入到细节，可能会过渡占用其他参会者的时间；具体的解决方案可以在会后找相关人员一起过下



##### 使用在线会议室作为团队固定的讨论空间

###### 场景：

团队在办公室里，可以在任意地方和任意的人
针对当前的问题
实时发起一个讨论，即时也避免了思路的切换。

而在 WFH 期间，每发起一个专题讨论都需要花时间拉起专门的视频聊天，邀请并等待参与者加入进来；很多氛围在等待中就渐渐的凉了。

###### 解决方案：

在这里推荐使用 zoom。在 zoom 里，我们可以为每个团队构建一个在线会议室。

这个会议室长期存在，可以用于站会、Code Review、集体讨论等场景。

而站会后，需要协作/讨论的团队成员可以留在这个会议室中继续，减少了远程协作过程中更换视频会议导致的重新聚拢参与者，重启话题等切换成本。

经过实践我发现，对于固定时间的团队会议，有了固定的会议室后，会议的准时率会有很大的提升。



##### 通过电子可视化恢复团队协作的场景感

###### 场景：

在办公室里，我们会建立各种物理设备进行可视化我们保证沟通是基于共同上下文，清晰可理解的

例如：

* 我们早站会时候，会在物理墙前对着负责的 Story ，描述”已经做过的事情，将要做的事情，提出困难和风险“ 
* 我们早站会时候， 会在对应 Story 上花正字核对点数，以及Story的状态
* 每个团队都有自己的 CI 屏幕以供团队随时确认自己的CI状态
* 我们的会议室里会提供白板、纸笔等供我们在讨论的时候更清晰的表达

而在 WFH，这些都没有了~~~~危害么，大家想象一下对着一个黑屏滔滔不绝的感受

###### 解决方案：

* 使用电子工具重建物理墙——可以采用的工具 Jira，Azure Devops
  我所在的团队PM在站会上使用的是 google sheet 表格，这个表格横纵分别是日期和人员名称，每个单元格内填充对应的团队成员在当天负责的事情；如果是 Story 的话，还会将这个Story 理想人天标记在上面。对于追踪工作进度而言，这个表格的信息一目了然；每天站会对着这个表格也很有仪式感
* 为每个人构建 CI 状态提示 —— 这里推荐使用的 BuildReactor  这个chrome 插件。BuildReactor 支持 Jekins, Go Cd 等 CI/CD 工具，可以选择关注哪些 pipeline；pipeline 挂掉、修复都有有通知发出
* 使用在线画板来将讨论内容可视化 —— 简单时候可以使用 slack、zoom的 annotation 功能将讨论的重点标记出来；对于大规模的协作，可以使用 mural 、 process on 等在线绘制工具来绘制 图表、UML 图来讲表达内容可视化出来
* [teamretro](https://secure.teamretro.com) 来帮我们完成一次成功的线上 Retro



##### 使用日历/提醒来提高勾搭协作的成功率

即使在办公室期间，团队已经习惯了使用 Google Calendar 来管理会议。

在 WFH 期间，这种方式带来了很明显的好处：

* 在指定会议时间的时候，Calendar 会提示这个时间与会者是否空闲，减少会议冲突
* 在确认会议邀请的时候，可以看到是否和现有会议冲突
* 会议的发起人可以确认与会者是否确认参加，并及时协调
* 明确的会议日程列表，供团队成员在上工前管理自己的一日时间分配
* 团队成员可以将不希望被打扰的时间标记在日历上，分享给团队

Slack 的 reminder 也是一个很好用的轻量级日程管理工具，我们将例如每日站会、Code Review 这些固定的集体日程发布到 Slack 的 reminder 中，尽量保证团队成员在工作时间只需要关注 Slack，可以保持专注。

而非固定的、个人的、需要协调时间的日程放到 Google Calendar，更好的协作。

多说一句，推荐一下[MEGAEASE的远程工作文化](https://coolshell.cn/articles/20765.html) 中 Review文化里对议题的讨论，这段内容可以帮助我们组织一个问题明确、节奏清晰的远程会议。

 

《人月神话》在讨论估算时候就指出：对于软件项目而言，工作量的一个隐藏来源是项目内的相互交流协作。

在我看来，团队的协作成本 = 协作规模（参考人月神话） * 人的协作能力（[MEGAEASE的远程工作文化](https://coolshell.cn/articles/20765.html)） * 办公环境下的沟通成本。

以上的实践是针对沟通成本的，只是治标。

规模、 人员能力是协作的本质复杂度来源；
而我所在的团队能在 WFH 期间成功的继续业务，背后的根因：
在长期的敏捷实践后，团队控制了协作的本质复杂度。

我也期待软件开发团队，在疫情过后，能够从这两点思考未来的建设方向。



