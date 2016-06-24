#IOS学习知识点梳理：
1、GCD学习推荐网址<br>
http://www.cocoachina.com/industry/20140428/8248.html<br>
2、Runloop学习推荐网址<br>
http://www.cocoachina.com/ios/20150601/11970.html<br>
3、Runtime学习推荐网址<br>
http://www.cocoachina.com/ios/20141106/10150.html<br>
4、Block学习推荐网址<br>
http://www.cocoachina.com/industry/20130605/6340.html<br>
5、改变网络环境工具<br>
注意：如果你是在真机上运行应用，而且网络活动发生得太快以致难以观察 completionBlock 被调用的时刻，那么你可以在 Settings 应用里的开发者相关部分里打开一些网络设置，以确保代码按照我们所期望的那样工作。只需去往 Network Link Conditioner 区，开启它，再选择一个 Profile，“Very Bad Network” 就不错。
 
如果你是在模拟器里运行应用，你可以使用 来自 GitHub 的 Network Link Conditioner 来改变网络速度。它会成为你工具箱中的一个好工具，因为它强制你研究你的应用在连接速度并非最佳的情况下会变成什么样。
