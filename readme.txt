


这个存储库用来记录那些具有年龄歧视的公司，看似年龄歧视是一家公司的自己的内部选择，但这选择的背后显示出的是对技术积累的蔑视，与这样的公司合作会对自己的资金和投资方的资金安全带来不可估量的风险。

所以这个存储库不仅是求职者对要入职的公司的一个预评估(好像"人力资源"行业有一个名字叫"背景调查")，
也能让重视自身商业信誉和资金安全的公司在选择合作伙伴时也可以有一个大概的预评估，以免对方收了你的钱、耽误了你的时间，最后做不出合同商定的产品。

如果你知道哪个公司存在年龄歧视的情况，就可以把那家公司放进这个存储库里。

一家公司一个文件或者文件夹：
文件名用公司名命名，即可以采用txt纯文本方式(这样几乎在所有设备上都是可读的)，也可以采用html等富文本方式，如果你决定采用富文本方式进行存储，需要将这个文件对应的css、图片、等与这个项目相关的内容放进 对应的公司名.d/ 这样命名方式的文件夹中。注意：避免全摊在根路径，因为这样会给别人造成困扰，而且很容易被别人覆盖、或删除掉。

对于同一个公司，为了区分修改后的版本与原版本，我们采用： 8位序号+公司名+修改日期+后缀 的命名方式进行命名。
例如，我要提交两家公司，第一家公司采用txt纯文本格式，第二家公司采用html格式，就是如下的目录结构
00010001 示例公司全名一 20251001.163000.txt
00010002 示例公司全名二 20251001.170000.d/
  index.html
  0001.css
  0001.js
  images/
    1.jpg
    2.png

8位的序号是顺序递增的，从 00000001 开始。



任何人都可以向我们提出 pull request .
操作方式如下：

--> 如果你已经被加入到了协作者列表中的话，请按下面的步聚提出 pull request :
git clone git@github.com:evil-trap/Age-discriminatory_companies.git
git checkout -b <你将来要提交PR的分支名称，比如：my-feature>
git diff
git add <changed_files>
git commit -m "提交描述，尽量做到言简意赅，以免被repo误认为是垃圾提交"
git push origin my-feature

----> 如果提交时发现 main 分支有了新的commit更新，就多做这几步：
git checkout main
git pull origin master
git checkout my-feature
git rebase main
有可能会出现 rebase conflict
这时需要一个个手动选择保留哪一行
git push -f origin my-feature



--> 如果你还没有被加入到协作者列表中的话，就用下面的方式提出 pull request :
用浏览器打开存储库网址
https://github.com/evil-trap/Age-discriminatory_companies
在右上部找到 Fork 按钮就点击
这样做的目的是为了让你获得一个有完整权限的存储库。所以你可以想怎么改就怎么改。
改完之后，先推回(push)到你自己的存储库中。就是你刚才fork回来的那个有完整权限的repo中
然后就可以在你自己的github账户中找到那个fork回来的repo，你会在绿色的 <>Code 按钮下边靠左一点看到一个 Contribute 按钮，点它你就会看到绿色的 Open pull request 按钮了，点它就能提出 PR 了
如果我们觉得可以合并进main的话，你就会在我们做完merge后收到邮件通知和github的站内通知。
之后你可以选择删掉你fork的repo,这样就不会在下次提交PR时导致分不清的情况了。同时这也会减掉我们主repo的Fork的数值，所以我们并不是以此来增加fork量的。







