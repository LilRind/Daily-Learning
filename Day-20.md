今天看了下游牧人的视频：https://www.bilibili.com/video/BV1zZcYz1EMy/?spm_id_from=333.1387.homepage.video_card.click
这个项目是利用Claude Code + GLM-5 + Anthropic的一篇文章（https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents）构建的AI全自动构建执行任务、构建系统。

目前AI顶尖公司都在构建Agentic Engineering，尤其是解决多Agent协作、多Agent一致性、上下文压缩导致上下文模糊、多Agent长上下文腐烂等问题：
可参考：https://www.douyin.com/user/MS4wLjABAAAAX4enn5sxJQWvIqyONRmab7wNVacTbrmAXJXAfaR6ENM?from_tab_name=main&modal_id=7604517615100251428
https://www.douyin.com/user/self?from_tab_name=main&modal_id=7598879809187433766&showSubTab=favorite_folder&showTab=favorite_collection
目前多Agent有一个共同趋向是：角色准确定位，例如：负责写代码的角色、负责测试的角色，子Agent往往是不参与代码的编写，而负责文件读取之类的不需要“隐性”同步的操作，单Agent负责重要的写操作往往会更好。

成果：完成了2个Task并commit&push，准备之后再进行实验。
项目地址：https://github.com/LilRind/auto-coding-agent-demo
<img width="1456" height="1034" alt="62457d63861d2bfeaee07451e8867c78" src="https://github.com/user-attachments/assets/43e74d03-763a-4222-8a16-33eeb46b2dbe" />
<img width="2419" height="1259" alt="b236ad7d52530d2bdff4ca11d9f768a4" src="https://github.com/user-attachments/assets/8f860f42-b12d-4c95-8568-8d641ace66aa" />


