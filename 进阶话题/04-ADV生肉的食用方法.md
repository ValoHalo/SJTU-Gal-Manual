# ADV生肉的食用方法
笔者：一抹多大好き

我们将那些没有官中或者民间汉化组汉化的游戏称为生肉。不同于汉化好的游戏通常提供的是打包好的汉化硬盘版，直接解压完即可运行游戏，生肉的食用略微繁琐一些。特别是现在随着ai补丁的大量涌现，并且其通常要求与日文原版游戏配合使用，所以生肉的获取、安装和使用的方法被更多的旮旯玩家所需要。这里为方便大家食用生肉，从源头获取开始为大家介绍相关教程。
## 获取
前文中已经提到了资源获取的相关途径，这里重新着重说一下生肉资源的获取。首先最传统的获取方法是购买galgame实体，通过光盘里的安装程序进行安装（但是由于各种限制，国内玩家较难得到实体，所以大多数人不会通过这种方式进行生肉安装）。当然现在越来越多的厂商也会发售dl版的资源，通过dlsite、dmm games等平台或厂商自己的网页进行购买和下载，这种方式不需要得到实体便可进行相关安装（具体内容可见后文的入正板块，这里不多加赘述）。而最后的也是最常用的方法，就是在相关资源站寻找大佬们放流的生肉资源。笔者常用的生肉资源站有[绯月论坛](https://bbs.kfpromax.com/)（通常多种下载方式度盘、微软盘、mega盘等等，但是现在注册后限制较多），[ggbases](https://www.ggbases.com/)（磁力链接，不需要注册），[nyaa](https://sukebei.nyaa.si/) （磁力链接，不需要注册），[anime sharing](https://www.anime-sharing.com/)（网赚盘不太推荐，不需要注册），[真红小站](https://www.shinnku.com/)（比较简陋，直链下载，不需要注册），[2dj](https://bbs4.2djgame.net/home/forum.php)(磁力链接，不需要注册)。其中绯月论坛和2dj的放流速度最快，通常新作发售的几个小时内就有人放流，而一些古早冷门作可以在ggbases和anime sharing碰碰运气。
## 安装
### 装载虚拟光驱
通过上述方式我们会得到压缩包形式的文件，解压之后一般内容里包含有大小较大的iso文件（游戏内容）和较小的mds文件（校验文件）。当然根据厂商的不同你可能发现解压出来的内容里并不是iso文件，而是mdf/cue/bin等后缀的文件，其实这些文件与iso文件的本质是相同的，都是 galgame的镜像文件发挥着光盘的作用，后续的处理方法也都一致。后面以iso文件为例讲解安装的流程，mdf/cue/bin等文件按照相同的方式操作即可。

安装的第一步通常是镜像文件的装载，这一步就像是在光驱中插入光盘，其作用是让电脑读取镜像文件中的内容。那么如何装载这个镜像文件呢？时间回到十几年前的话，我们是需要用到虚拟光驱软件的。但是现在无论是win10还是win11的自带的 file explorer（也就是文件资源管理器）已经自带了装载虚拟光驱的功能，只需要对着iso文件右击鼠标，再点击装载即可（没错，就这么简单）。但是之前有人问过我，为什么我也是 win10/11，右键的选项里没有装载呢？

<img width="496" height="217" alt="图片" src="https://github.com/user-attachments/assets/b1607a07-2ddb-40e6-a71b-88e18c44e306" />

右键没有找到装载的情况

其实这里你只需要点开打开方式，在里面选择Windows资源管理器打开即可。

<img width="608" height="385" alt="图片" src="https://github.com/user-attachments/assets/a5a6af7c-2eac-40c9-b357-fdc38a4f955c" />

通过打开方式选择 Windows资源管理器打开

当然，有人可能想说，我还是想要右键一下就能看到装载的选项，该怎么弄呢？那我们就打开系统设置，依次点击应用、默认应用、按文件类型选择默认值，找到.iso，将默认应用设置为 Windows资源管理器。再返回我们的iso文件，右键后我们就可以看到选项中出现了装载了。这样设置完成后点击装载，甚至直接双击iso文件即可完成虚拟光驱的装载。

<img width="958" height="544" alt="图片" src="https://github.com/user-attachments/assets/04163205-1e70-4945-ad8e-4a61d005b0de" />

系统中设置应用打开方式

<img width="1005" height="119" alt="图片" src="https://github.com/user-attachments/assets/da556af0-26e8-4d65-8c0d-7bd8e14040d3" />

设置iso文件默认用 Windows资源管理器打开

<img width="809" height="294" alt="图片" src="https://github.com/user-attachments/assets/629fc855-3655-45b6-9a9c-a71b8e9abcba" />

设置完成后的右键选项

除了windows自带的资源管理器之外，我们也可以使用一些专门的虚拟光驱软件如DAEMON Tools Lite，相比Windows的默认方式，它支持更广泛的格式，如.mdf、.cue、.bin等。随便搜索免费版或者破解版均可，安装完成之后右键可以发现打开方式中多出了 DAEMON Tools Lite的选项，点击即可完成装载。同样的你也可以在系统中设置 iso等格式的文件默认用 DAEMON Tools Lite 打开，这样设置完成后同样可以双击iso文件就完成了装载。

 <img width="758" height="31" alt="图片" src="https://github.com/user-attachments/assets/9f731642-d5fb-4323-9770-8e6e89202060" />
 
通过打开方式选择 DAEMON Tools Lite 打开

 <img width="1005" height="105" alt="图片" src="https://github.com/user-attachments/assets/bbce6e71-b389-47bd-a442-dc28e37de10a" />

设置iso文件默认用 DAEMON Tools Lite 打开

通过上述的方法完成镜像文件的装载之后，我们可以发现在文件夹左侧多了一个驱动器，点开这个驱动器，我们可以看到其中存在有setup.exe（也可能叫别的名字），至此，我们的安装进入到下一个阶段。

 <img width="340" height="217" alt="图片" src="https://github.com/user-attachments/assets/5c51311d-f39e-4071-b419-675e9001aca4" />

装载之后出现新的驱动器 

<img width="961" height="400" alt="图片" src="https://github.com/user-attachments/assets/8ffbc73e-04fd-4f09-936d-a41610d1bc26" />

点开驱动器后的大致内容
### 安装程序
不同于一般软件的安装直接双击setup.exe即可，galgame的安装需要用到转区软件（[Locate Emulator](https://github.com/xupefei/Locale-Emulator)（LE）和[Locate Remulator](https://github.com/InWILL/Locale_Remulator)（LR），少部分安装程序可以不需要转区，或者不能转区，但是这里还是建议大家优先转区打开安装程序）。具体转区打开的方式也很简单，以《鬼父》为例，我们首先打开驱动器（如下图中我们应该打开红色框选的部分，而不是黑色框选的部分，双击黑色框选的会直接打开安装程序，双击红色框选的则进入上图中的文件列表）。

 <img width="1005" height="338" alt="图片" src="https://github.com/user-attachments/assets/96cc2899-5be7-4415-bbd2-bae9f2a7356a" />

打开驱动器

接着我们对setup.exe右击，可以见到选项菜单中有事先安装好的 Locate Emulator（LE）和Locate Remulator（LR），进一步点开选项，可以见到下图的各类选项，通常先使用 Locate Emulator的Run in Japanese（admin）（因为使用 Run in Japanese 进行安装有些时候会失败报错）如果使用LE进行安装没有反应时，可能的原因之一是软件是64位软件，使用LR的 Run in Japanese（admin）进行安装。

<img width="1005" height="459" alt="图片" src="https://github.com/user-attachments/assets/a8093006-438e-49fa-8049-a06bc0224f3e" />
<img width="1005" height="459" alt="图片" src="https://github.com/user-attachments/assets/ba35714e-73ff-4430-b7de-920d73e6bc22" />
使用转区软件打开安装程序

通常来说打开之后会弹出一个警告，点击“是”即可，之后会弹出安装的弹窗，一直点击下一步到实行即可即可。

<img width="497" height="411" alt="图片" src="https://github.com/user-attachments/assets/a441a10f-a4a0-4e89-a3ee-6eb44cb0f3eb" />

跳出的警告

<img width="627" height="315" alt="图片" src="https://github.com/user-attachments/assets/c127f81d-1f27-48ee-882a-696a864a2fcc" />

安装程序的弹窗

像我们之前所提到的，有些游戏它并没有setup.exe，并且安装的界面更加复杂一点，不是直接跳出安装的弹窗，下面以《初恋サンカイメ》和《 sin 光臨天使エンシェル・レナ ～REINCARNATION～》为例进行说明。我们看到驱动器里没有setup.exe，取而代之的是初恋サンカイメ.exe，我们同样采取上面的方式用转区软件打开。

<img width="1005" height="548" alt="图片" src="https://github.com/user-attachments/assets/1fe1b3a0-94a0-406c-998d-6c517b30e496" />

没有 setup.exe的情况

<img width="919" height="473" alt="图片" src="https://github.com/user-attachments/assets/dfc2d6c1-5500-48d6-8fa8-558d0a315aed" />

打开后程序的界面

打开之后出来的是一个界面，这里我们点击最上面的（インストー儿 /安装）。同时附上一些常见的对应词（来源贴吧）。

```
ゲーム (Game) – 游戏
インストー儿 (Install) – 安装
セットアップ (Setup) – 安装 / 设定
起动（きどう） (Activate) – 启动/开始
スタト (Start) – 开始
终了（しゅうりょう） (Finish/End) – 完结
中止（ちゅうし） (Stop/Terminate) – 终止
キャンセ儿 (Cancel) – 取消
始め（はじめ）（ (Begin) – 开始
続け（つづけ） (Continue) – 继续
メニュー (Menu) – 菜单
ロード (Load) – 读取
セーブ (Save) – 储存
入力（にゅうりょく）(Key In) – 输入
データ (Data) – 资料/档案
上书き(うわがき)（ (Overwrite) – 盖过/取代
タイト儿 (Title/Title Page) – 标题/标题画面
次へ（つぎへ） (Next) – 下一页
戻る（もどる） (Back) – 回头/上一页
…ない (makes negative) – 不(反义词)
```

点击安装之后会跳转到下一个界面，同样一直点击下一页，一直到最后的完成，等待安装完成即可。

<img width="754" height="431" alt="图片" src="https://github.com/user-attachments/assets/173e0280-3c37-4329-be53-275365cc20a7" />

<img width="756" height="466" alt="图片" src="https://github.com/user-attachments/assets/62e1c9d1-0c71-4a0b-b5b7-183930a3d525" />

安装的界面

光临天使的安装界面虽然略有不同，但是整体方法也是一样的。这里比较清晰的一点是我们点击界面中黑色框选的部分，然后点击参照，可以自定义安装的路径，别的安装程序大多也都有此功能。

<img width="874" height="725" alt="图片" src="https://github.com/user-attachments/assets/e489d80e-d9f2-4a0a-84df-31ae52413afb" />

设定安装路径

### 特殊情况
通过上述的方法基本可以满足大多数生肉安装的需求。但是存在着一些安装情况较为特殊，因为情况各异且较少出现，这里只简单说明其中的一些情况。1. 部分镜像文件不是只有一个iso文件，可能被分为了两个iso文件，一般名字为XXX_disk1.iso，XXX_disk2.iso。这种情况下我们需要先使用上面处理单个iso文件的方法处理 XXX_disk1.iso，一般安装到一半的时候，它会跳出一个弹窗，弹窗的大致意思就是让你换成disk2文件继续安装，这时不要关闭这个弹窗和安装程序。右键驱动器图标，弹出装载的disk1文件（我们可以看到下图中这个驱动器的盘符是E）。接着我们装载 XXX_disk2.iso（因为我们是先移除再装载，所以disk2文件的盘符应当也是E），不需要打开新装载的驱动器，直接回到之前的安装弹窗，点击继续安装即可，等待安装完成（有群友之前和我反应过同时装载disk1和disk2到不同盘符如E和F同样可以继续安装，但是最正规的方法应该是按照上述的操作进行，出错的概率更低）。

<img width="695" height="506" alt="图片" src="https://github.com/user-attachments/assets/1a83b31f-9e90-45fb-b88f-3f5e04f06779" />

弹出disk1

另外还有一种情况是在镜像文件中打开安装程序没有反应或者在安装阶段就出现仅限日本地区使用或者需要进行验证，而我们后续用到的破解补丁、 NoDVD补丁等是无法移入到虚拟光驱的（因为它是虚拟的，而不是一个实际的盘符）。出于这种无奈的情况，我们可以尝试一种方法，就是直接对iso文件进行解压（下图展示的是mdf格式的镜像文件，各类镜像文件都可以这么操作）。解压之后我们可以看到安装程序，在这里进行破解。有的还直接包含了游戏本体的内容和游戏运行的程序，可以直接打上 NoDVD补丁进行运行（如下图中的AdvHD.exe）。但是必须要强调的一点是，直接解压的方法是我们迫不得已的情况下才采取的措施，任何时候建议先采取上述正常的安装措施进行安装，尝试无果之后再进行解压，不然可能会出现各种错误。

<img width="1005" height="484" alt="图片" src="https://github.com/user-attachments/assets/09bd93bd-dcc4-4dd0-bd18-08f29e189793" />

对镜像文件进行解压

<img width="1005" height="409" alt="图片" src="https://github.com/user-attachments/assets/d9c764f7-28a0-402b-b496-681af8f81679" />

解压后的结果

### 安装破解补丁

当我们将游戏安装之后是否可以直接开始玩了呢？答案通常是否定的，因为游戏的厂商大多加上了验证保护（也有一些游戏没有保护，直接运行程序转区就可以启动），需要输入序列号或者检验区域，所以我们此时就需要破解补丁（注：如果你之后还要使用AI翻译补丁的话，请根据AI补丁里是否包括了破解跳过下面的破解步骤，如果你想玩日文原版或AI补丁中不包含破解请继续看下去）。目前来说获取相关破解补丁最全面的地方就是[2dfan](https://2dfan.com/)。我们进入2dfan的网站之后就可以在顶部的搜索栏搜索需要的破解的游戏，以《 sin 光臨天使エンシェル・レナ ～REINCARNATION～》为例，搜索之后我们点击下载后的“其他”选项。跳转之后可以找到破解补丁/免DVD补丁，点击进去下载。

<img width="927" height="532" alt="图片" src="https://github.com/user-attachments/assets/86ff11d4-aa36-46f2-9e9e-b46b550fdec9" />

搜索游戏

<img width="476" height="231" alt="图片" src="https://github.com/user-attachments/assets/ba5823dd-43c8-4329-99be-26a412871546" />

找到破解补丁

<img width="858" height="123" alt="图片" src="https://github.com/user-attachments/assets/1728d9f9-9626-4af7-b48d-7e26da280cab" />
下载破解补丁

下载完成之后我们得到的是一个压缩包，解压之后，通常而言有两类形式的破解补丁。一类是已经封装好的破解补丁，解压后得到的是一个与游戏运行程序类似的exe文件，样貌如下图所示，对于这一类破解补丁，我们直接将其复制到游戏的根目录下（有你的游戏运行程序的文件夹），接着鼠标右击破解补丁，选择LE或者LR转区运行即可（这里我们通常优先使用 Run in Japanese ）。

<img width="938" height="388" alt="图片" src="https://github.com/user-attachments/assets/b18d4fe3-d3b0-4f37-82e4-b89fd9cba442" />

下载后压缩包中的内容（封装的破解补丁）

<img width="591" height="338" alt="图片" src="https://github.com/user-attachments/assets/f6a867d7-5511-4f30-9067-461d8ee75e6b" />

复制到根目录转区运行

<img width="644" height="167" alt="图片" src="https://github.com/user-attachments/assets/10fc7892-4392-4e01-a3d5-6d25e9ba67a3" />

成功运行

此外还有一类破解补丁是只有破解程序，其模样通常如下图所示。对于这一类破解补丁，我们不能直接转区运行它。我们首先同样将其复制到游戏的根目录。然后，我们用鼠标左键点住游戏的运行程序不要松开，将其拖拽到破解补丁上之后再松开，之后一直点是完成破解。破解完成之后，我们转区运行游戏原来的运行程序即可打开游戏。

<img width="650" height="526" alt="图片" src="https://github.com/user-attachments/assets/874b169e-e482-4fa1-8409-e4caf37060a2" />

下载后压缩包中的内容（未封装的破解补丁）

<img width="650" height="606" alt="图片" src="https://github.com/user-attachments/assets/0b0ee776-e719-472d-a5b7-7697a3ea0691" />

拖拽运行程序进行破解

<img width="650" height="512" alt="图片" src="https://github.com/user-attachments/assets/6e7c4484-8a1c-4752-bc00-b0a46ed4074d" />

转区运行原运行程序

<img width="1005" height="295" alt="图片" src="https://github.com/user-attachments/assets/ba1b4c24-fa04-4d21-ae01-cdfb8bfcb925" />

成功运行

## 使用AI游玩生肉
如果你是想要玩日文原版游戏，所有步骤到上面已经完成，可以开心游玩了。如果你想结合AI食用生肉，还请继续看下去。
### 使用AI补丁
基于现在大模型的迅速发展，不少高质量的AI翻译补丁涌现，不少生肉资源已经有AI补丁可以使用，所以我们首先讲如何获取AI补丁。目前AI补丁最全的网站是[2dfan](https://2dfan.com/)（因为一些破事导致许多AI补丁被删除），[鲲站](https://www.moyu.moe/)（同样和前面的破事有关），[御爱同盟](https://www.ai2.moe/)（推荐，最早的ai补丁站）。这三个网站中都在搜索栏中进行搜索后，找到相关的资源，之后下载即可。

<img width="783" height="656" alt="图片" src="https://github.com/user-attachments/assets/e5543340-5d7f-4f7e-97c9-db5125fa5aa0" />

<img width="974" height="688" alt="图片" src="https://github.com/user-attachments/assets/988a4dbb-ef7e-444a-bfa5-69c41bc73d85" />

鲲站的补丁下载

<img width="953" height="163" alt="图片" src="https://github.com/user-attachments/assets/f45cd465-0b34-4567-8f31-244bbd30b03a" />

御爱同盟的补丁下载

之后与破解补丁类似。下载完成之后我们得到的是一个压缩包，解压之后，各类AI补丁的内容各异，但是总体而言也是分为两类形式的AI补丁。一类是已经封装好的AI补丁，解压后其主体内容是一个与游戏运行程序类似的exe文件，样貌如下图所示，对于这一类破解补丁，我们通常直接将其解压后的所有内容复制到游戏的根目录下，然后按照补丁作者的要求进行操作（一般是安装相关字体等，否则可能会出现乱码），根据要求看是否转区运行AI补丁（此类封装好的AI补丁通常不需要你进行前面破解的操作，一般它已经完成了破解）。

<img width="709" height="449" alt="图片" src="https://github.com/user-attachments/assets/30802a5d-3c6f-41c3-8877-c2fd823bb56a" />

封装的AI补丁（有些只有一个exe文件，有些和图中一样还有别的文件）

 <img width="800" height="73" alt="图片" src="https://github.com/user-attachments/assets/1a1ef29f-7722-4966-b21f-66f47e80f000" />

补丁中的内容都复制到根目录

 <img width="591" height="143" alt="图片" src="https://github.com/user-attachments/assets/b655c537-0f3e-4e67-aeb1-f42b3b9029f0" />

 <img width="650" height="388" alt="图片" src="https://github.com/user-attachments/assets/964ae285-b415-4da0-a0a4-cb18e5695a50" />

根据要求进行操作，安装字体和是否转区运行

<img width="709" height="195" alt="图片" src="https://github.com/user-attachments/assets/de3058e9-93c1-48e1-82be-a625bdaa191b" />

成功运行

同样与破解补丁类似的是，有些AI补丁是没有进行封装的。这一类AI补丁我们解压之后里面通常是没有exe格式的运行程序的（如下图所示）。此类补丁通常是将补丁中的所有内容复制到游戏的根目录进行替换（建议提前将会被替换的原内容进行备份或者改名，方便后续恢复）。然后按照补丁作者的要求转区或直接运行游戏的原运行程序。

<img width="709" height="339" alt="图片" src="https://github.com/user-attachments/assets/37ad42c1-1ba1-4afe-b51c-9667610fc96d" />

 
未封装的AI补丁（通常没有运行程序）

 <img width="650" height="361" alt="图片" src="https://github.com/user-attachments/assets/6de2b3bf-34cf-4755-9038-f16795fdd400" />

补丁中的内容都复制到根目录（提前做好备份）

 <img width="886" height="138" alt="图片" src="https://github.com/user-attachments/assets/0cbf4ef4-22bd-427e-8c8e-dbbb92bd4581" />

成功运行
### 使用本地大模型实时翻译

目前许多的生肉都已经有人做了AI补丁，但是还是有少量生肉没有AI补丁，或者有些人想要同时看日语原文和翻译，这时我们就需要挂载实时翻译了（在大模型出现之前，这种方式是日语苦手啃生肉的最主要或者唯一方法，AI补丁出现之后，现在逐渐用的越来越少了）。关于这一领域最有名的软件就是VNR，但是其使用略复杂，对新手不太友好，我们这里介绍[LunaTranslator](https://docs.lunatranslator.org/zh/)，软件的下载和安装请安装超链接的教程进行，我们这里主要介绍如何使用。

下载完LunaTranslator后我们双击打开，点击齿轮的按钮进行设置。进入后核心设置基本不需要动，通常情况下我们的文本输出都是用的HOOK既准确又快速，只有在后续过程中HOOK不到正确内容的时候我们才会使用OCR（其本质就是读取你框选的内容，然后对其进行文本识别然后翻译，其速度和准确性较HOOK而言都要差，而且需要额外的OCR的api，所以我们后续都以HOOK的方法进行说明）。

<img width="915" height="384" alt="图片" src="https://github.com/user-attachments/assets/652e8f13-4615-48ae-be28-c20bc7c4582e" />

打开程序的设置

<img width="915" height="507" alt="图片" src="https://github.com/user-attachments/assets/509526a9-6074-455e-ae62-383b8d9cf82f" />

核心设置

在显示设置中选择是否显示原文，以及根据自己的喜好对原文和译文的字体、大小、颜色进行调整。

<img width="915" height="424" alt="图片" src="https://github.com/user-attachments/assets/c37f6090-2535-40ac-937c-034670a4e445" />

显示设置

在文本处理设置中可以勾选文本预处理中的处理重复行和重复字符，这类情况在HOOK中偶尔会出现，其余情况通常较少出现，可根据情况勾选。后面的各项设置通常用不上。

<img width="915" height="488" alt="图片" src="https://github.com/user-attachments/assets/aeca680b-9edb-4856-9eae-65c4e1289aec" />

文本处理设置

最重要的就是翻译设置了，点开翻译设置，最上面的就是大模型设置，下面的则是传统翻译设置。因为如今大模型的翻译效果明显优于传统翻译，所以这里只介绍大模型的设置，传统翻译可自行申请api进行添加。

<img width="635" height="548" alt="图片" src="https://github.com/user-attachments/assets/d835f1a4-1ee3-43c3-b499-6b63ccd98494" />

翻译设置

首先是大模型通用接口，其中需要我们输入API的接口地址和API，具体内容可见[LunaTranslator的官方介绍](https://docs.lunatranslator.org/zh/guochandamoxing.html)。 这里可以是那些官方提供的满血大模型的API，也可以是那些可在本地部署的开源小模型。考虑到GalGame的巨大文本量，除非你是钱包十分充实或者追求最佳的翻译效果，否则不太建议使用在线的API。对于本地部署离线大模型，官方提供了三种方法，这里我们介绍其中的[ollama](https://ollama.com/)。我们打开ollama官网之后，点击download，选择自己的系统进行安装。

 <img width="886" height="418" alt="图片" src="https://github.com/user-attachments/assets/d04886dc-91b9-4a3d-806e-993f90ba983b" />

大模型通用接口介绍

 <img width="886" height="416" alt="图片" src="https://github.com/user-attachments/assets/1dda8593-e4cf-45a3-846b-19554333cf26" />

ollama官网
安装完成之后，我们回到ollama的官网，点击左上方的models，再从表中选择自己想下载的模型**（需要说明的是本地部署大模型对于显卡的显存有着要求，这里推荐显卡至少有着8G的显存才尝试进行大模型部署。8G显存可以部署各种7b大模型，16G显存可部署各种14b大模型，后续的SakuraLLM也是这样的）**。这里以deepseek-r1:14b为例。我们复制右上角的命令行，接着在随便一个文件夹的空白处右键，选择在终端中打开，打开powershell，然后填入之前复制的命令行，等待大模型下载安装完成即可。

<img width="886" height="149" alt="图片" src="https://github.com/user-attachments/assets/4023fa45-9e22-418c-beef-e8ea32c329de" />

 
选择想使用的大模型

<img width="886" height="149" alt="图片" src="https://github.com/user-attachments/assets/68b13bb0-cc10-4e0d-b4e8-ee26ffa9a176" />

下载并安装大模型

安装完大模型之后，我们可以在 powershell里填入ollama list并运行，查看已经安装的大模型名称。接着我们输入 ollama serve运行ollama，其中能看到host为：`http://127.0.0.1:11434`（默认地址，如果你没有更改的话应该也是这个）。最后我们打开 LunaTranslator翻译设置里的大模型通用接口。API接口地址填写： `http://localhost:11434/v1/chat/completions`；API Key不填，model填写 ollama list里的name列，我这里选择的是：huihui_ai/deepseek-r1-abliterated:14b 。后面的各项可以不变，这样就设置完成了。但是值得一提的是大部分大模型现在有着思考的过程，这会导致出翻译的速度较慢，会比较严重的影响游戏体验，所以我更推荐下一节要将的Sakura大模型。

<img width="886" height="118" alt="图片" src="https://github.com/user-attachments/assets/0371f002-1493-450f-9f08-12dd3f5ea53f" />

查看已安装的模型名称

 <img width="886" height="153" alt="图片" src="https://github.com/user-attachments/assets/fb536039-54dd-42b2-a624-9fa48e2494f7" />

运行ollama

 <img width="886" height="704" alt="图片" src="https://github.com/user-attachments/assets/8a7f0dba-1798-4241-ab1d-9c5cdb0f6f09" />

填入设置

关于Sakura大模型的使用同样有多种方法，这里就介绍相对简单的[Sakura GUI启动器](https://github.com/PiDanShouRouZhouXD/Sakura_Launcher_GUI)的使用方法。首先下载并安装[Sakura GUI启动器](https://github.com/PiDanShouRouZhouXD/Sakura_Launcher_GUI/releases/latest)，安装完成后我们双击点开，进入界面之后选择下载，分别在Sakura模型下载和llama.cpp下载中选择自己对应的情况（显卡是A卡还是N卡，显存8G对应7b模型，12G以上对应14b模型）。下载完成之后进入启动界面，分别点击刷新，选择对应的模型和显卡，高级设置，记住host和port，默认情况就是`http://127.0.0.1:8080/`。全部完成后点击粉色的启动即可。然后我们返回Lunatranslator，这次我们选择大模型下的Sakura大模型，点击齿轮进行设置。设置里填入刚才记下的API接口地址，默认情况就是： `http://127.0.0.1:8080/`。以及选择的模型，后面的选项可以不做更改。这样设置就完成了，每次运行先打开Sakura GUI，点击启动，再打开Lunatranslator即可。

<img width="694" height="620" alt="图片" src="https://github.com/user-attachments/assets/a4bb3202-3b4b-491b-803e-7153687e80eb" />

Sakura模型下载

<img width="632" height="705" alt="图片" src="https://github.com/user-attachments/assets/76d47972-8583-4710-8a13-839a7e4cba47" />

Llama.cpp下载

<img width="781" height="734" alt="图片" src="https://github.com/user-attachments/assets/f79df312-3b0c-4af1-9023-f5a0ee857d93" />

启动界面的设置

<img width="983" height="614" alt="图片" src="https://github.com/user-attachments/assets/ef94db7f-3a44-457e-a9b4-c5e47b929439" />

Luna的Sakura模型设置

完成上述的大模型设置之后，我们在翻译设置里点开要启用的翻译（笔刷前的那个东西），LunaTranslator支持多翻译同时进行，我们再点击笔刷设置不同颜色即可比对各个翻译来游玩了。完成翻译的设置后，我们转区运行我们的生肉游戏，以《Circus Disk -Christmas Days-》为例，游戏运行后，我们点击LunaTranslator的选择游戏选项（ 游戏机图标和三本书图标中间的那个，此外LunaTranslator的图标可能被隐藏了，可在页面右下角找到）。找到我们的游戏进程单击后选择OK，进入到选择文本界面。这时我们返回游戏界面，启动游戏，点击几次对话（建议将游戏的文本显示速度设置到最快）。在文本界面中选择与对话内容完全一致的点击显示选项即可（多个完全一致的情况只需要选择一个）。如果有内嵌的选项点开的话，翻译内容则不是外挂的，而是替换到游戏的文本框中，表现出与翻译补丁类似的效果，但是内嵌的情况容易出现各类bug，请酌情使用。点击显示之后，我们关闭文本界面，继续点击，即可出现翻译，展示图中蓝色字体是Sakura7b模型的翻译，而绿色和灰色是传统翻译，可以看到哪怕是7b模型的效果也要强上许多。至此生肉的食用部分结束。

 <img width="221" height="193" alt="图片" src="https://github.com/user-attachments/assets/62b2b4ec-34e4-4137-bf61-f3016773c20f" />

找不到 LunaTranslator 的图标

<img width="1005" height="72" alt="图片" src="https://github.com/user-attachments/assets/41ffad58-bcab-4902-bf16-17a030ee8c52" />

选择游戏

 <img width="903" height="489" alt="图片" src="https://github.com/user-attachments/assets/44418c93-4ba0-4475-b9cb-d9a134b6933c" />

选择游戏进程

 <img width="676" height="791" alt="图片" src="https://github.com/user-attachments/assets/635c381d-20b9-4410-a7de-b71fe1f6645a" />

选择文本

 <img width="884" height="498" alt="图片" src="https://github.com/user-attachments/assets/40f2541a-b206-4e1d-833f-ccacbb0dc765" />

效果展示
