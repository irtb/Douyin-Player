# Douyin-Player
我们很多人日常中都爱刷抖音：看直播、关注他人、和粉丝/好友留言点赞互动，一刷就停不下来，这样很容易造成手指骨折。鉴于此，我写了一个自动刷抖音的程序。主要用到的是图像识别和匹配等知识。如果有兴趣探究，那么在节省手指的同时也可以锻炼自己的大脑。总之，这是一个有利于我们身心健康的程序。：）
# 使用注意事项
1. 解压flags.zip，里面是用于匹配各个页面的“靶图”，放到一个你认为风水比较好的文件夹。

2. dyauto.py是主程序，也是唯一的一个程序。把里面的一些目录换成你的靶图文件目录，具体是哪里好汉应该一看便知。

3.涉及到需要点击的地方都采用adb shell + 坐标的方式。提供了两套坐标供参考：HUAWEI MATE20 物理手机（1028x2244）和MUMU安卓模拟器（1440x900）

4.为了尽量贴近无人值守，在页面匹配技术上选择了图像识别/匹配而非UI xml文件类。 想学习数字图像的强烈推荐本程序作为起步研究材料。

5.最后一步：运行程序，如果出错，那么就排错。

# 实测效果

手机连上电脑后，运行程序放了一个晚上，粉丝由300涨到1100，粉丝互动火热。

# 声明

1.靶图文件涉及到的页面截图都是随机截取，如果抖音号拥有者觉得不妥，别犹豫，马上告诉我换图。（其实，用你的截图对你来说这是一个多么好的涨粉机会啊，～～哈哈）

2.请勿将此文件用于商业用途，如果非要用的话，那么...感谢认可，我主要担心非但商业没辅助上，反而赔了。

# 鸣谢

-感谢我家两个娃儿的懂事，她们在我几天的写程序和调试程序期间找我说话多次被我无情地拒绝，然后她们并没有生气，只是说等我忙完再和我说

-感谢娃儿的妈妈，在我写程序和调试程序期间每天做饭（但是碗还是我刷的）

-感谢我的dy好友们，有时候我看似在看你们直播，其实我在调试程序，希望你们不会看到这些话。用善意的谎言骗一个人一辈子，那么这还叫骗吗？ 深了...深了...

-感谢自己对这个程序写了大量的细节注释，哈哈...

