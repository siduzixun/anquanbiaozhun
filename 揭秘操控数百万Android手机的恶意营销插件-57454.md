# 声明 
本文是学习[揭秘操控数百万Android手机的恶意营销插件. ](https://siduwenku.com/view/55036?f=new_2023)而整理的学习笔记,分享出来希望更多人受益,如果存在侵权请及时联系我们
# 总结  
  
随着移动互联网的飞速发展，用户规模不断增长，金融、生活以及社交和娱乐等全面向移动互联网迁移，这也导致移动互联网各类应用爆发式的增长。其中不乏大量利用用户对娱乐、色情产生依赖而生的黑灰产类恶意APP。而这类APP为了缩短开发成本和提高开发效率，大部分会接入第三方公司的SDK（软件开发工具包、插件）。并且这种开发方式已然成为开发者常用的开发方式。当然万物有利有弊，某些组织受到利益的驱动，甚至开发出暗藏恶意的刷量、扣费及窃取隐私等的恶意SDK。这些黑产类SDK除了被黑产人员用在自己的恶意APP中以外，还会被不知情的开发者接入，从而影响使用其APP的正常用户，甚至造成下架停运的风险。  
  
而“道贼”SDK功能强大，编写非常专业，并且运用多种免杀对抗手段。如果没有长时间的积累和相关娴熟的分工配合是不可能开发实现的，于此亦可窥见现今移动端黑灰产已有想到成熟的积累。  
  
针对普通用户如何避免遭受诸如“道贼”恶意插件的侵害，奇安信病毒响应中心移动安全研究团队给出了以下防护建议：  
  
1\. 使用正版和较大的官方应用市场提供的APP应用，不要安装非可信渠道的应用、不要随意点击不明URL链接和扫描安全性未知的二维码信息；  
  
2\. 移动设备及时在可信网络环境下进行安全更新，不要轻易使用外来的网络环境；  
  
3\. 确保安装有手机安全软件，并进行实时保护；  
  
4\. 若发现手机感染木马病毒，请及时使用安全软件进行清理，避免重复交叉感染。  
  
另一方面，作为一家安全厂商里专门进行移动互联网安全研究的团队，奇安信病毒响应中心移动安全团队一直致力移动安全领域及Android安全生态的研究。目前，奇安信的移动安全产品除了可以查杀常见的移动端病毒木马，也可以精准查杀时下流行的刷量、诈骗、博彩、违规、色情等黑产类软件。  
  
奇安信病毒响应中心移动安全团队一直以来致力于持续跟踪分析全球范围内的移动安全威胁活动趋势以及研究移动互联网相关的安全技术。我们也在今年年初发布了2019年移动安全总结报告[1]，详细描述了2019年国内外的移动安全事件、威胁活动以及奇安信内部跟踪的移动安全攻击事件和APT攻击活动，对2019年移动互联网安全进行了详细总结。奇安信病毒响应中心会持续走在全球移动安全研究的前沿，第一时间追踪分析最新的移动安全事件、对国内移动相关的黑灰产攻击进行深入挖掘和跟踪，为维护我国网络安全砥砺前行。  
  
# 附录  
  
## “道贼”SDK相关IOCs  
  
| **文件Hash**                      | **AppName**                                                                                                                                   |  
|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|  
| 7c480ad464c8094d4e85853f8f64fcaf | 123啪啪                                                                                                                                       |  
| caa13aa8cf7cffa2624a02c12644a14d | 149代刷网                                                                                                                                     |  
| 9d7fc91dfd8a2af2cbc5b2365da2367f | 18禁片吧                                                                                                                                      |  
| 67ef9dee3957487509ffe6c3753dac9f | 4399单机游戏                                                                                                                                  |  
| fd0a906d38cfde06c64bf30d40003552 | 4399游戏盒                                                                                                                                    |  
| d676de1834886439d1b9d8eda97c8d02 | 522漫画免费版                                                                                                                                 |  
| 5f30e1e49c178feb18b0e6d7de655175 | 5GNEWS                                                                                                                                        |  
| 8c506dfa785181d72fdcb127e1fe43f7 | 8800AA                                                                                                                                        |  
| 0f65cd2014a5f8ecce6aafcd0ee8037f | 91漫画破解版                                                                                                                                  |  
| 1bbd04bc9a5e989ca47f8b466eb290db | AJHOME                                                                                                                                        |  
| 2052d81dff09cd08d01b9e4a38bd44c3 | D2天堂短视频                                                                                                                                  |  
| 18e7a87628c326767c50e91352156f13 | ExaGear - Windows Emulator                                                                                                                    |  
| dfbf5d4b3e2761bed2508bf93eb3976f | F2富二代                                                                                                                                      |  
| 8c88572669354d22a591baea8e7c5b51 | F2富二代学习资讯                                                                                                                              |  
| 0f6e00aad331e25c0788e5969ba64fae | game center                                                                                                                                   |  
| 42c5578f6cbcaca755f876e36173c9ac | game center                                                                                                                                   |  
| 981fab654831bf06c99b75cdf1377d6c | game center                                                                                                                                   |  
| 1eb5aa9f6d3972d2e3a601c2697c4b22 | GameGuardian                                                                                                                                  |  
| 0900fdf16582ed09b43bff54842fa2b9 | gdsr                                                                                                                                          |  
| 20a8efccee828bc67a2668bde3e4130c | gdsr                                                                                                                                          |  
| 33c2df755f094be3b77428b8983358f1 | gdsr                                                                                                                                          |  
| 3a912170515e3549cc5d0d0ab4734e02 | gdsr                                                                                                                                          |  
| 4bfafde53f3be0fb6b145ee32b30582f | gdsr                                                                                                                                          |  
| 8ffa6bbbceaf5edc65cce7b048c2c4d8 | gdsr                                                                                                                                          |  
| ceb016e515c3ad06c8dc7b2f46f30757 | gdsr                                                                                                                                          |  
| cfefed326a86e1f73c51289ad6127b69 | gdsr                                                                                                                                          |  
| e06c8c73e24f3dd492ddb7ea051c7c79 | gdsr                                                                                                                                          |  
| f05b7b0f7ea34bff1f1b9645f76a1eda | gdsr                                                                                                                                          |  
| 9c761d3d15ee30994722623c818796b2 | Kino Baxlan                                                                                                                                   |  
| 48b5abd174157e2f41fd0d3ac15bcf5b | literature                                                                                                                                    |  
| 2d97ef4479ca2ca352760a35bba191c2 | lzamyiutdvkr                                                                                                                                  |  
| 0393db5fc98b75a48081dd5fc8b1664a | Mark                                                                                                                                          |  
| 076ddd9f10a54b1b87f3294b1bc6658b | Mark                                                                                                                                          |  
| 0b051069907aa4a6c645623c98b6e947 | Mark                                                                                                                                          |  
| 288d2e0ba1f372414509d9cde481b301 | Mark                                                                                                                                          |  
| 2b4386bfb7f72d2d493f6ad24342b438 | Mark                                                                                                                                          |  
| 343b3b836ac7525b4e12b820f8c09c49 | Mark                                                                                                                                          |  
| 60a53406d90fa0ba4b9259a29c104781 | Mark                                                                                                                                          |  
| 62ea6c59592cf73c53ce6e7d8ae9f647 | Mark                                                                                                                                          |  
| 63ca36f3d4c3f90319a69f3880fbb2eb | Mark                                                                                                                                          |  
| 887992600f4d9a5ae7d57267b7cd2099 | Mark                                                                                                                                          |  
| 98c65b232e10eb9efca2000a1922dad6 | Mark                                                                                                                                          |  
| aa6de479139cafaf07ae63f4f17d37fc | Mark                                                                                                                                          |  
| bf3a9263aa4ea30d4ccc0e6e2edef420 | Mark                                                                                                                                          |  
| c3f75115cfc17ce43dfdf161c1d305a0 | Mark                                                                                                                                          |  
| c97df21fed26b0d08a2592992f62db53 | Mark                                                                                                                                          |  
| e020069361afcc4192f4f16f8220e839 | Mark                                                                                                                                          |  
| f3082c0e42e324fdddb4856c5d499e78 | Mark                                                                                                                                          |  
| fcfcbfedc89b294d89af2236bf787744 | Mark                                                                                                                                          |  
| 85786960bd45ba8977942be28c637ae9 | MC小锦代刷                                                                                                                                    |  
| b5f2a3e236cd9762917b619580dc075d | MyMovie                                                                                                                                       |  
| 9b2552337afb93a97dc52b0eb2aa753c | NFC                                                                                                                                           |  
| dea343bd88f2ab554bf6f341e6fd555d | NFC                                                                                                                                           |  
| 14a90805cf8230c21d95d29482f81bd3 | Planner5d                                                                                                                                     |  
| 63f9b40ef2149fa17a5c07fe14dab208 | QNine                                                                                                                                         |  
| 09bdb8ce5c11f6feaf629ba2a6d9079a | QQ代刷商城                                                                                                                                    |  
| 2049671f5ab8cb02356e1e868a11ca66 | QQ代刷商城                                                                                                                                    |  
| 20ee58ee59b42571c467914f65d70559 | QQ代刷商城                                                                                                                                    |  
| 216edd7f9b4d16ca6e851066cbb22d42 | QQ代刷商城                                                                                                                                    |  
| 3320b6b3a258a5cae075a6cd236143f7 | QQ代刷商城                                                                                                                                    |  
| 3a518612fb6f21a88b1a66a3781a47a5 | QQ代刷商城                                                                                                                                    |  
| fa0e734934af2ac700a5c686713d4b01 | QQ代刷商城                                                                                                                                    |  
| bafdf87411362e599bf5423b9ac2befb | QQ代刷网                                                                                                                                      |  
| e40804e60ef4f3deebc19bb5ec1ceca7 | QQ代刷网                                                                                                                                      |  
| 4679a99e602c53f9bc350090129b8c6c | QQ代刷网商城                                                                                                                                  |  
| c73258e10f1dc2eba75d9db933f4ed31 | QQ代刷网商城                                                                                                                                  |  
| acea5738d59d9881ff54ce1bc1677845 | SoftPoint                                                                                                                                     |  
| 686bfb4563b6079db4583a31dbed3baa | svip                                                                                                                                          |  
| b273df585d2ceac5f9649c5c1b16ba51 | sVip                                                                                                                                          |  
| 6fb61252a963dfe209c424387a1ab7f3 | VIP影院                                                                                                                                       |  
| 9be6afe31242945c8535be0375a56579 | WWE摔角网                                                                                                                                     |  
| 069051cc6683578cdab603bac4ba6264 | yuchuang2                                                                                                                                     |  
| 47885dfdccae4ba6a52fe1e78821a829 | 阿里星球                                                                                                                                      |  
| cf2516eec3b5378a5a0ce0dc44d67f19 | 爱美剧                                                                                                                                        |  
| 8be0dcca1de85fd58ad2ad6ad0e784db | 安利头条                                                                                                                                      |  
| 8b27f25d844cc44596d984fca4f1dafe | 安玺云阅读                                                                                                                                    |  
| 99613f81aa7ed83c705fa2e56ee5e02a | 安卓手游2                                                                                                                                     |  
| 2d14b48e41be3e0a7a54fa37bfb0f127 | 奥特曼格斗进化                                                                                                                                |  
| 1695956c10f7db60f00fc8e9f7612517 | 仿冒百度                                                                                                                                      |  
| 0fa197bb418edc336627360b0e69ed37 | 本子库                                                                                                                                        |  
| 4d3356dc681a629ddacfebac0bf37f5f | 比特狗                                                                                                                                        |  
| 1a8e44c0d2362e0f9c8e681334c97cd6 | 哔咔Picacg漫画                                                                                                                                |  
| e4d2c8f6e4fb40abbc7c869006ab67b2 | 哔咔漫画app                                                                                                                                   |  
| 734c8e6ec335f0afbf3d19a8f67ac8d2 | 啵乐                                                                                                                                          |  
| cb5802d97203e4ad6c6987c32eb0c0b6 | 啵乐                                                                                                                                          |  
| 81ddf4e2606999efb6fd31060c204ed9 | 啵乐漫画app                                                                                                                                   |  
| 4f3252222b055652608b160ea56e2330 | 彩虹小马                                                                                                                                      |  
| 9afb7538359a2d8c8fdd505b86e963d2 | 彩虹小马                                                                                                                                      |  
| e106badb88abc1510fc97650492a1970 | 彩虹小马                                                                                                                                      |  
| ff98234dee8760dd7cfbe30a2684e268 | 超级人脉                                                                                                                                      |  
| 14d06f5b9687671a28a7d1d75e9c2c1b | 超级商城                                                                                                                                      |  
| 3b9ac184bd7230ca6bccfb7bf07cc3ca | 超蜜趣                                                                                                                                        |  
| 477f9ecf22fdf54be653bf127850275f | 超蜜趣                                                                                                                                        |  
| 6ee431e78846cb77a17891ebdbb2650f | 超蜜趣                                                                                                                                        |  
| d28b6f9001399ae29bb331367846aaeb | 超蜜趣                                                                                                                                        |  
| 65c945a223069f77f97619241d4c7efe | 诚信代刷分站版                                                                                                                                |  
| 4ba81a93f44091e53a70115a1213dea5 | 承运商测试版                                                                                                                                  |  
| 7693404eeae3989e58f51310c6d4d92c | 承运商测试版                                                                                                                                  |  
| b46cbbd06d72c87a732d963952e7c6c9 | 橙子视频                                                                                                                                      |  
| a8d418de016e50cff1ae0343e93c9a3e | 从师求学                                                                                                                                      |  
| f9c6fb66c870146ff9a27066b9aaaf8b | 大工·失物招领                                                                                                                                 |  
| 40a860595ca6f8e37f8b9ef3949c5cb8 | 大圣轮回bt版                                                                                                                                  |  
| 8e17e984063ce2e3779733863ea070c4 | 代刷网平台                                                                                                                                    |  
| 3a3f78fa8a707d5aba94f31df5ec605a | 代刷网社区                                                                                                                                    |  
| f57526fff11a862a529d8acb30ff8991 | 代云影视                                                                                                                                      |  
| 5790ed4f117564088f441eefc0086094 | 袋熊视频                                                                                                                                      |  
| 2b1c2193cd1b017b0e331a686822b39e | 单机斗地主（开心版）                                                                                                                          |  
| c8d9e5973e1a37b6f8b5da12335438d8 | 单机斗地主（开心版）                                                                                                                          |  
| d89978c259a1bbc497fdee40af418d31 | 单机斗地主（开心版）                                                                                                                          |  
| a97de70a3b4bf95e08aae6824f7a57e6 | 单机斗地主单机版                                                                                                                              |  
| aa8f3a374b8492f974bd38d4b0fcd07c | 单机游戏中心                                                                                                                                  |  
| e832041339ad2dde4726f40dbf7ae106 | 帝一娱乐                                                                                                                                      |  
| 7cb27e2c582083ad5be5e88293e9b70c | 第二369                                                                                                                                       |  
| d623ec2c1b3c56df97d016afe84757f6 | 第二课堂中小学登录                                                                                                                            |  
| fab43f5816d76d6143d18477cb5a221d | 东盟网                                                                                                                                        |  
| 7bfcb33ef1ae05bd0653bc377ecb5f0b | 凡星代刷                                                                                                                                      |  
| c6a288a563e7f26f354cb758e05c3d25 | 粉色哔咔                                                                                                                                      |  
| 1ed69840ef4402d5c565ad8edbfa0755 | 疯狂牧场                                                                                                                                      |  
| 8bf697e776bd56420c85f24863cf70b7 | 福社生活                                                                                                                                      |  
| 2b604f5fd155f2ea0cdcd0d79d99dcfb | 腐次元app                                                                                                                                     |  
| 1830b906af0917ad5f64654577e44f96 | 高清观影                                                                                                                                      |  
| f03954bd81967f5738d3c39d070e826a | 高效待办                                                                                                                                      |  
| 077db8497cdf3c2d2923096d0a4e5b81 | 光速代刷网                                                                                                                                    |  
| f1a3b7985b32de9ef9e95b7a80e5fe17 | 闺蜜视讯                                                                                                                                      |  
| fa5a59e11772a2fd91529773225988a4 | 闺蜜视讯                                                                                                                                      |  
| 88e26bd66661cdfb7d9353f5187b9b3a | 过冬在线观看                                                                                                                                  |  
| c968e770e2b4aab5975aa66fc8b81804 | 海试优品                                                                                                                                      |  
| 04637797f11e4f938662ed4912efb0ac | 航天模拟器                                                                                                                                    |  
| ca0998021d8e8c2cc9707b9a0edc551a | 豪华竞速                                                                                                                                      |  
| e20b058dd84dfd982f98b3d2e80a4edb | 好牙医招聘网                                                                                                                                  |  
| 8968d9183f4d8da4d9b9b8e6a91e4990 | 黑洞大作战                                                                                                                                    |  
| 48c10df0a67550711f21772b4a763c18 | 嗨漫漫画                                                                                                                                      |  
| 36de239ea4ba08639bcc839082dc620d | 嗨享                                                                                                                                          |  
| 9f3cc1e151735f69aa0daf6d663be325 | 恒大恒房通                                                                                                                                    |  
| 6ec2c11efd62a631f6f06be170ff0c36 | 鸿润商城                                                                                                                                      |  
| b391f203eadf05a6f3f68e83ffc14ac6 | 华夏万象                                                                                                                                      |  
| 3252ca45af83d6c1f0a537f75c00942b | 欢乐斗地主闪电版                                                                                                                              |  
| e4205356e441138483ba5764e0f74653 | 欢乐斗地主闪电版                                                                                                                              |  
| 1fb92fdce3f1f0e98ca5d3b31ee7be39 | 欢乐竞技斗地主                                                                                                                                |  
| 37fecf25e2e56fc284e56c42dfc87d4a | 欢乐竞技斗地主                                                                                                                                |  
| 89166699fe59f9b9f5d76f8aa8ae8748 | 欢乐竞技斗地主                                                                                                                                |  
| 8de35872837ed6e46db85fde63d581b6 | 欢乐竞技斗地主                                                                                                                                |  
| c0723dff9429e6d5b41eb4ebe8bf6c52 | 欢乐竞技斗地主                                                                                                                                |  
| 61ec6f44ad24140fceefb96dc82d9eef | 欢趣禁片                                                                                                                                      |  
| 76518958534ef1eabc7742d117d460ce | 欢趣禁片                                                                                                                                      |  
| 711cf3219747c08b729f934e0a815f3b | 欢色神器                                                                                                                                      |  
| bb7fc4b8fbea5dc5d3ca1e22141640b6 | 黄黄放映室                                                                                                                                    |  
| 61ecb966523dd62db237685cfbb80545 | 黄黄美片                                                                                                                                      |  
| d09b9de3c83ca2b38022181dbc36605b | 火热艳影                                                                                                                                      |  
| 443170f30e0989a35dfc0267bba4f816 | 火星影视                                                                                                                                      |  
| d87520a5d549e943f97db11e1bbccab4 | 火影忍者高招模拟器                                                                                                                            |  
| 9757c7205b974a8a562c2fcf13b1e017 | 火影同人忍者后宫                                                                                                                              |  
| 197b04613cc913e423ab64667455fd3a | 激活美女                                                                                                                                      |  
| 2dfa8a26c8fb7dc7f1b130c28681d1ad | 激活美女                                                                                                                                      |  
| 2e282dca23e7bc4c774dd5cb5f26efe7 | 激活美女                                                                                                                                      |  
| 30c8a871136621f55856eb21e670fd9c | 激活美女                                                                                                                                      |  
| 3b9d114ae00e7ad68cac7d357acdedd6 | 激活美女                                                                                                                                      |  
| 5a6f3e695ee94f601df82e2a2f472b87 | 激活美女                                                                                                                                      |  
| 71eeb411dfcf1be9595cc3a594901d52 | 激活美女                                                                                                                                      |  
| 72e2270d97e2406820dc21ba7212046f | 激活美女                                                                                                                                      |  
| 866f5aa87ffde4dc4b7c1018591ae60c | 激活美女                                                                                                                                      |  
| 96abb4f380c39d44eb3ac680ac1ecac3 | 激活美女                                                                                                                                      |  
| 9ce3a018bb171c0157ea7de439f4a85a | 激活美女                                                                                                                                      |  
| c50de6d65b0918c97cab8599d4340649 | 激活美女                                                                                                                                      |  
| e476469e2fee84bc43126480c5ec6245 | 激活美女                                                                                                                                      |  
| 7d3ffe3e27ab58b6d0f721fb3b675d0a | 激爽神器                                                                                                                                      |  
| 4b4226a9a66715d341ddbf757c742bfc | 极速网络助手                                                                                                                                  |  
| fa52d2d9a1a2a069472ff94bfa5f71a1 | 节奏                                                                                                                                          |  
| 406dd52f185c558a6e65ee33ee89c754 | 姐姐禁片                                                                                                                                      |  
| 3419f1daefb2a13301c3a99a4a58b1b9 | 今日资讯                                                                                                                                      |  
| 7cfca4577ec389f93fff0b7dcff2c3ed | 今日资讯                                                                                                                                      |  
| e6d7735126b87c9a5707f6868606bc14 | 今日资讯                                                                                                                                      |  
| 020b8dfbf49f853521c5c839e86ff6e1 | 禁女美影                                                                                                                                      |  
| be78b0d2d8096ce6461d3464b11a8ce2 | 禁女美影                                                                                                                                      |  
| 43bf8fd077387aa04f03b3cd66639e35 | 禁止片吧                                                                                                                                      |  
| a214d12152ded06b89a7353c599f6645 | 聚宝鹏托管                                                                                                                                    |  
| 7dc5b377471473d23cac8bad0f556001 | 绝地求生：刺激战场                                                                                                                            |  
| b01fb1546ce4f0f402595230dc238d88 | 绝地求生：刺激战场                                                                                                                            |  
| 31583fe93eb916ffa71051a85356f149 | 可乐网盘                                                                                                                                      |  
| 78b5ff580f8d020402ad21a7157d5a64 | 可乐网盘                                                                                                                                      |  
| 0ef8ffff911d5e2d2c3e152801e85625 | 恐龙有钱                                                                                                                                      |  
| 4660d007346f16f559aa3774fdb32613 | 库乐队                                                                                                                                        |  
| cab8ea74717fd562aa6a5182c9ad4122 | 夸克浏览器                                                                                                                                    |  
| 64666ca80aafeb3cf351f6249ac7c52f | 快乐斗地主二打一                                                                                                                              |  
| aeed42442091a102f9654c3e3304eeb0 | 快乐斗地主二打一                                                                                                                              |  
| e0b927aab07749c0f21e8818812d6772 | 乐购365商城系统                                                                                                                               |  
| 0a551a4f9fc3a19cac705fc281de70f1 | 离殇代刷网                                                                                                                                    |  
| e7aa29dc1d6549150a849237f1556aa8 | 李晓航代刷网                                                                                                                                  |  
| 02af3808091a0ee5c506a6026001bc77 | 连线达人                                                                                                                                      |  
| 6a9cbfc18486b28c7dea7017f7d55a95 | 连信                                                                                                                                          |  
| 9f85a039b52b3080154fd18c5945386e | 连信                                                                                                                                          |  
| e69493773e4f2cb6f5084aa79572243f | 恋恋花名册                                                                                                                                    |  
| 86bf7302395b512a588c049494dd0738 | 留雨云带刷                                                                                                                                    |  
| 157aed28200ae51f8ec6ba0e54ba4bbe | 龙门汇                                                                                                                                        |  
| 3b8b60dbc75000f6a1e985db8ada3ba8 | 裸聊美女                                                                                                                                      |  
| d1c72eb69a536920be61e38a399c461d | 马哒社区                                                                                                                                      |  
| 83ca17d2d8faf3d2af595c93d54ff925 | 芒果TV国际                                                                                                                                    |  
| 8251255dd129e84e4e943afd96b9be55 | 猫叫模拟器                                                                                                                                    |  
| 3c7c59d8c1757dcaef2d95130a8ca43e | 美剧鸟                                                                                                                                        |  
| 429d513db10f731bfd1330dd0240fe7c | 美剧鸟                                                                                                                                        |  
| 92caca8a495e69a538bb0ff25269caf2 | 美剧鸟                                                                                                                                        |  
| baf26825360ae79d6f71021e10964b34 | 美剧鸟                                                                                                                                        |  
| c11161ff26996de7941f20c66e790cea | 美剧鸟                                                                                                                                        |  
| 368fe709bfcb6e52022d93b3e63db66e | 美剧影视                                                                                                                                      |  
| 52c7cdb463be285f9192894e9acdb17d | 美女剧场                                                                                                                                      |  
| 31efaee1da10fe8dd676d1c03957c2c0 | 美女束缚                                                                                                                                      |  
| b586543763913072a99c3a4b09133f6b | 美女束缚                                                                                                                                      |  
| c3ebc41cea3b6ef024ea882cf3b24d42 | 美女束缚                                                                                                                                      |  
| d8b11a753f13936ec9d11414d31ab879 | 美女束缚                                                                                                                                      |  
| cb8bac0143d207df2968706fe4188a91 | 美色色影                                                                                                                                      |  
| 263d5503f87f6765e0fe7095337227c6 | 妹妹艳片                                                                                                                                      |  
| b3b723e21479c92fda29fbddf373d338 | 媚情放映器                                                                                                                                    |  
| fd56e80a95045e47613f639fbd5aa507 | 媚色影片                                                                                                                                      |  
| 03038ab0ecd9ada1a01ff619338a845e | 魅力影院                                                                                                                                      |  
| b63cabc58e5485b125e69c4bd7f70eb3 | 魅趣放映器                                                                                                                                    |  
| fc72459f053c57b016cc9fe98ce8197f | 萌乡绅士仙女次元                                                                                                                              |  
| 28453ea72676a333a0de880a70d0badd | 梦幻花园                                                                                                                                      |  
| 04b982b7491af87b903c04f6dac609f0 | 咪咪剧集                                                                                                                                      |  
| c8c3b2c5e6ba1bd76dfc1a139837fb5b | 咪咪神器                                                                                                                                      |  
| 63d10244a415680e5a9916476a982cbd | 迷爱视听                                                                                                                                      |  
| cbc472d644245ff02370d9d884aeba1a | 迷你世界2                                                                                                                                     |  
| 1066ba118368a99d902fe12a23965f40 | 秘密剧场                                                                                                                                      |  
| 46763cfb86e8778543f28a417dfee9f5 | 秘密剧场                                                                                                                                      |  
| 87fbfe7c001a999ccb3e85b9b59ca19f | 秘密剧场                                                                                                                                      |  
| f491313e94c2778621a92d3f678b2edd | 密爱魅影                                                                                                                                      |  
| 046fa246a6496ca39e8addbf4e76abb6 | 密爱视吧                                                                                                                                      |  
| 4b4e8d9ad91e1f20c1269b20bb63538d | 密爱影音                                                                                                                                      |  
| bf34b777c7a037cb0d977ae9d1093103 | 蜜色片库                                                                                                                                      |  
| 45cb4e13a6848ad05f91f5a96b1712fe | 蜜水剧集                                                                                                                                      |  
| 0c8cef4c3e167eb0e3be054322e08787 | 蜜享                                                                                                                                          |  
| 9d167939398b8973c0af346985469a5b | 免费柬团测试版                                                                                                                                |  
| 5f0dfa3ff3cdd6c5d5b97da290a900a7 | 喵喵代刷网                                                                                                                                    |  
| c6fdb7f38f7f8ed69ddb1a35535df4bf | 名片赞                                                                                                                                        |  
| 2c14dbf3c0d06fcbc8db202930e15d2e | 魔域来了                                                                                                                                      |  
| 5fac76d59f105911b479cfa0820f18ad | 墨迹代刷                                                                                                                                      |  
| 3b7866ec8a9db9b3eda525fbe6641886 | 墨宵后台                                                                                                                                      |  
| bd9515831a9bc57de39cec1fafbb4a92 | 男欢波吧                                                                                                                                      |  
| 13830b2c831290a495298b9716f6632c | 南瓜影视                                                                                                                                      |  
| cb078834c89ecd2ea33dda3cd028059c | 能源国际                                                                                                                                      |  
| fe9fdd4408d2de0f64ef63eece29a02a | 尼米代刷                                                                                                                                      |  
| 1fefed4ba77771a23cd36c3cbe28824a | 牛顿的眼泪                                                                                                                                    |  
| 245d0c4ebb696a54c888496122d13422 | 女爱美影                                                                                                                                      |  
| d23499596c48d9a507aab7a13c67d84f | 女女片吧                                                                                                                                      |  
| c0a114322b21d09273d63a935aa2d940 | 女色色影                                                                                                                                      |  
| 2ff77b0a805b32d6ddf66856c5f19cda | 皮逗影视                                                                                                                                      |  
| a61271e74da41faed850fabb0498cfb0 | 皮皮漫画                                                                                                                                      |  
| c3d6ce564ef2bdd402378cac86366490 | 皮皮漫画免费版                                                                                                                                |  
| 557a9351be4f7479b90a72a91ce3db70 | 浅梦刷单商城                                                                                                                                  |  
| 1047567b8216efd5c97c8a5ef01b6e1b | 情爱波放器                                                                                                                                    |  
| 18083e8d8acebd4093bfbe8de3d3c36b | 情趣片库                                                                                                                                      |  
| 2c209a9296625fdc9a0d557e3f40b5a8 | 秋天的小店                                                                                                                                    |  
| 798c109797018678d32a154a03d36f2b | 趣享                                                                                                                                          |  
| 8273108281efa58e1bbc93828923c648 | 趣享                                                                                                                                          |  
| 1274ed8cea7e206026ae6e92043707b5 | 色女TV                                                                                                                                        |  
| 7039e8f6dbe0f4406cf3bee9c1be180c | 色夜片吧                                                                                                                                      |  
| c6bb09c561c22a3802b6197a4dcc7077 | 色夜艳影                                                                                                                                      |  
| 53c06dedeaff6712a0e7b14a8446308d | 涩会波放器                                                                                                                                    |  
| 7e1d7df6e0afcc45e1f641cde1965a37 | 涩会剧集                                                                                                                                      |  
| 19278e313cbee7c92921444a8d614d0a | 少女波放器                                                                                                                                    |  
| 2716f190f6086a44d32077e56faaebeb | 少女都市3D                                                                                                                                    |  
| 33ef2c39cbe435cc6e79ccb634af97ef | 少女美视                                                                                                                                      |  
| 18cb456c2883d6f544dc7bd94401559c | 少女希尔薇                                                                                                                                    |  
| 69572887fd08e8cae0bc2b021a2e8b1a | 少女希尔薇                                                                                                                                    |  
| 89b60c38e1c335164e714711b53449a6 | 少女希尔薇                                                                                                                                    |  
| 89bda8e1d88cdb6dbe57bc8ed18e782a | 少女希尔薇                                                                                                                                    |  
| 8f7751fec1f3dce674b75fae71256b3b | 少女希尔薇                                                                                                                                    |  
| c985b5cf09ba280192da1bb85fc1e968 | 少女希尔薇                                                                                                                                    |  
| 470b92195ce1b693b48d6cbf8cf31bc0 | 社会摇后台                                                                                                                                    |  
| 4d302e60f3a744230142db38b3d4a03e | 绅士道漫画最新版                                                                                                                              |  
| e26eedc080c6af7248a26e55235cc95e | 神无月                                                                                                                                        |  
| b4bff0f5e2f51e75f0db689ddbac73d3 | 生活奇事网                                                                                                                                    |  
| 1d1ac505efdf59679b10cf72ad0247ec | 食色                                                                                                                                          |  
| 33eb41612002520203bd5b867bb55ca4 | 世界征服者3                                                                                                                                   |  
| 66870c01c23519e1d8947a303b8f3b03 | 守望黎明                                                                                                                                      |  
| 74f5c3aaa750c913dae5d2102e54c83f | 撕裂少女衣                                                                                                                                    |  
| d37fb32bea6e3c2f5d9ff7ba4967a859 | 死神VS火影全人物版                                                                                                                            |  
| 093dd9ca109d61e02606beac92ade6b0 | 搜狐资讯                                                                                                                                      |  
| 1e7503eb6226e9f4b806621061b4cc8e | 搜狐资讯                                                                                                                                      |  
| 3c9db1712d11507f91e7eb5243d40d41 | 搜狐资讯                                                                                                                                      |  
| 3de88877a269af028951932da711c8d1 | 搜狐资讯                                                                                                                                      |  
| 51cd2be8394a281f5fddd7f60d114827 | 搜狐资讯                                                                                                                                      |  
| 840cc5034fd9f427cfd13b5c94347a33 | 搜狐资讯                                                                                                                                      |  
| a5d348127e1ae3cabfbe61e735703a75 | 搜狐资讯                                                                                                                                      |  
| b4d373b90abecf3a7b939b319b1629a4 | 搜狐资讯                                                                                                                                      |  
| c219b3e74fe2d63ea60ef2a5b99d6a49 | 搜狐资讯                                                                                                                                      |  
| db5d6f06341e126f3d9166dda59009a0 | 搜狐资讯                                                                                                                                      |  
| ea16c0dd3f9f7ca332f5d0136345981a | 搜狐资讯                                                                                                                                      |  
| 0a4db6967c7a6edd506fb16bf361d1f5 | 速看影院                                                                                                                                      |  
| b934474dbbb04042c1f9266fb9bfa10f | 泰木谷                                                                                                                                        |  
| 4c256f7fa37f3f87a4ff0d2ed21b8d2b | 天台交友网                                                                                                                                    |  
| a2f5e09a901dd6c528976e2a31f94fa7 | 甜蜜影院                                                                                                                                      |  
| cbcc5b9aa4910b04e55af7710561a01a | 甜蜜影院                                                                                                                                      |  
| 47c869f3338e1a5b6b7bdc6840999795 | 甜甜美眉                                                                                                                                      |  
| 8aaebd69bcf22ab1281a38de78dac2f0 | 调休申请系统                                                                                                                                  |  
| 03bc508a839b6b5820f68cf99b3cc948 | 跳一跳                                                                                                                                        |  
| 27d74777e20e2f1602ee1b47bf42553d | 跳一跳                                                                                                                                        |  
| 7f5ff3cde4392ebda29cb54c9a158432 | 跳一跳                                                                                                                                        |  
| 6911744b43cf3e926c58cde2fbbf8102 | 跳一跳疯狂版                                                                                                                                  |  
| b8c3a06ff833ea8934a029c3d2b7f10e | 跳一跳疯狂版                                                                                                                                  |  
| 71647033d2d4a0fce2b5dd9ccb864ee8 | 歪歪韩国漫画                                                                                                                                  |  
| cd5e657ca8683d0cf3b9e91d441f0d67 | 万航影视                                                                                                                                      |  
| 8c9a345aefef4eb8f440c90eecb0b6c0 | 违法代码查询                                                                                                                                  |  
| 38bdd87fe2a3ceec8eb7f0b942b6490d | 我的世界                                                                                                                                      |  
| 26ae9f7d1451ed349dc0d595390fe5f0 | 我想当皇上                                                                                                                                    |  
| 86d5ddf991bca9220585e96b8c0fec73 | 我要当国王                                                                                                                                    |  
| cef1324a931b5a031fcc78d2feac6a1a | 污污漫                                                                                                                                        |  
| 59c933f3e4839948c7f692a06ee75ac9 | 午夜激情                                                                                                                                      |  
| ef7c5a60ef4b6f8b4785e9322f2e9343 | 午夜激情                                                                                                                                      |  
| 028aa15f45a7e98d7124a01491b156a7 | 系统升级                                                                                                                                      |  
| 24294b78de4e1d9de8a30ae93bc6fada | 系统升级                                                                                                                                      |  
| 51a4fe359ea420d807d36b76d1db3ef1 | 系统升级                                                                                                                                      |  
| 002196e8822d967e89140d821dc0b4ac | 下载猫                                                                                                                                        |  
| 33bd79f3341d093aa04054fbaa52e9e6 | 香草1对1                                                                                                                                      |  
| 03551e3cb110f93607996a7144c8dc5a | 香肠派对                                                                                                                                      |  
| d7bc1634ba5d33f5bf348ef36d87f622 | 香肠派对                                                                                                                                      |  
| 10ad89d500628af03d47cc8bfe225fca | 像素生存                                                                                                                                      |  
| 2f097b2eb440eae708a25566281fab9d | 像素生存                                                                                                                                      |  
| 5382d390b9e9d9b24b2996594fbc7fd8 | 像素生存                                                                                                                                      |  
| 5d0ea08c47b27a68f44354995c1bf65c | 像素生存                                                                                                                                      |  
| a65cd300f688d56eb00864ff58945843 | 小z影院                                                                                                                                       |  
| b3998894143f8b1eab4aa00b2ccad1e3 | 小白代刷网                                                                                                                                    |  
| 97b72675f93514f78644ff21aeeb6872 | 小飞侠                                                                                                                                        |  
| aae5ca58fc7135fdd37ff6e2dedaaa64 | 小鸡模拟器                                                                                                                                    |  
| 70103f636e3c4e44ef5d0e9403986f11 | 小梦代刷网                                                                                                                                    |  
| 375bcc72fe63de23663f462ba920c0e5 | 小全代刷                                                                                                                                      |  
| 00d18bed720d90cfb195e1223868e2f1 | 小说端子                                                                                                                                      |  
| 38e4533d9a67e974bea7e08192d558df | 小说端子                                                                                                                                      |  
| 8a701615a74ff52f4b75b8cfb3104f98 | 小说端子                                                                                                                                      |  
| 9948c779ece602c3adac012dbdc83a81 | 小说端子                                                                                                                                      |  
| b5d58c1067025f5a06ecef1747a1a77c | 小说端子                                                                                                                                      |  
| b9315a15b0e6b59adf67cfc9f7524b06 | 小说端子                                                                                                                                      |  
| d044a6782d81406be58bf3da61dfea76 | 小说端子                                                                                                                                      |  
| fbb366e37a8bcb3dee5d4666bd1f7685 | 小说端子                                                                                                                                      |  
| d92a0e753a8fd6df878f9fb4fed1d8e1 | 小小影视                                                                                                                                      |  
| 7a6c11b10cb77d842fdb0df9e79c2e65 | 校导                                                                                                                                          |  
| b5c05f56452dc10eb855bec4fb750f59 | 心动女友                                                                                                                                      |  
| b10d836ea87cc68b1db89b2e1cfe2c77 | 馨儿代刷网                                                                                                                                    |  
| 34b6ea21bf386289f0e2897179325677 | 星玛智能                                                                                                                                      |  
| 424d9cd27080833c7ea2ef8526076f14 | 性情看片                                                                                                                                      |  
| c17a4ce6972d9d34517f210693ccb685 | 颜夕社区                                                                                                                                      |  
| 15947b4d06fb07d83889d91ec3d5f8ad | 艳爱动作片                                                                                                                                    |  
| 8d58d61c4932eb93d937964822c5c589 | 艳女美影                                                                                                                                      |  
| 00339934d294689b54d3c5a649afcfac | 艳色剧场                                                                                                                                      |  
| e4565b0f013ccd0fa1006b6810d8d0eb | 艳夜色影                                                                                                                                      |  
| 2017466a49c80ac64aa108e95ea59299 | 夜蜜视吧                                                                                                                                      |  
| d7d41a46d209cc582b0372e839d970f2 | 夜情影片                                                                                                                                      |  
| 013444cf7ebc53bfe71f656a9c4a7911 | 夜色福利场                                                                                                                                    |  
| 0409dfe39a67f1e9b23f46fecf56d519 | 夜色福利场                                                                                                                                    |  
| 1210b4f3b3289bb93b06cbc3a569f0f4 | 夜色福利场                                                                                                                                    |  
| 5a92ab1de564435fd88b4732b89134cd | 夜色福利场                                                                                                                                    |  
| 88a9842172e7510d2a8341ae2c7221c1 | 夜色福利场                                                                                                                                    |  
| c4751e82d43232a0b994a0626b720d8a | 夜色福利场                                                                                                                                    |  
| 4c91715d71694f584373dc4241aedf20 | 易辰全民斗地主                                                                                                                                |  
| 99257e1647f0b168063e1eb0f89a76bd | 音悦球球                                                                                                                                      |  
| 61c8b078aae53a1a4183ae0b6e0dc930 | 樱花动漫                                                                                                                                      |  
| 1ccb17155b2bfcffebe9cfb1d46cf659 | 樱桃影库                                                                                                                                      |  
| ae2cf1126f38c00c6e5117367de7b533 | 拥挤人类                                                                                                                                      |  
| 56d8ff3434e4bef9edaf22f2ea501884 | 优速影视                                                                                                                                      |  
| 7e0aab5042ded7dffd967f2834cbc6a8 | 诱女禁影                                                                                                                                      |  
| 0ed7a9fc24da478f5da0e88d4bc6eb15 | 鱼塘                                                                                                                                          |  
| 185f03cb74cac9f3021b7a1d7b8c83fe | 鱼塘                                                                                                                                          |  
| 348cfaf4df49fe85b06d540532b1f6db | 鱼塘                                                                                                                                          |  
| 9635d4287aab3635ae46b303e542177d | 鱼塘                                                                                                                                          |  
| 086437f5ae03c7f252b5da7eb9fc286e | 欲望美眉                                                                                                                                      |  
| 7790d4bae209d3bbdd9e35a4ee407c2c | 欲望美眉                                                                                                                                      |  
| c9133f887839c1089be601a931bad5b2 | 欲望美眉                                                                                                                                      |  
| cb8b95d921fc8515a076f935aa544bb2 | 欲望美眉                                                                                                                                      |  
| e97be5d06bbcb863e256a3aed4020ced | 欲望美眉                                                                                                                                      |  
| 43a24f367e4bf0b00ad7a844c105eff9 | 月光宝盒                                                                                                                                      |  
| fd48a7922db9f2ff53df4a9575b5c4e1 | 岳城影视                                                                                                                                      |  
| de27992a057621df830e364405f125aa | 云电脑                                                                                                                                        |  
| c3b351626cb9c665ec06254cdcc20dc5 | 云岭先锋                                                                                                                                      |  
| 0f8cda466036da5d4e47ba8bb1307c41 | 造梦ol千骨修改器                                                                                                                              |  
| 04136e64e3a1a9ddecb86dce8632beeb | 章鱼哥                                                                                                                                        |  
| 59e716de49761bf91d422d9ef7fc48d4 | 正当防卫                                                                                                                                      |  
| a62b90706e0641d76193cb316c3e812e | 正当防卫                                                                                                                                      |  
|                                  |                                                                                                                                               |  
| **文件Hash**                      | **DownloadUrl**                                                                                                                               |  
| 03551e3cb110f93607996a7144c8dc5a | http://xt.codegmf.com/91617745-1.0.14.38-20190521.apk                                                                                         |  
| 7dc5b377471473d23cac8bad0f556001 | http://xt.codegmf.com/wdsjcjzcqmhz-91714116.apk                                                                                               |  
| 10ad89d500628af03d47cc8bfe225fca | http://xt.codegmf.com/szxmxwdsjx-91617500-1.0.13.28.apk                                                                                       |  
| 33eb41612002520203bd5b867bb55ca4 | http://xt.codegmf.com/91779201-1.0.14.34-20190423.apk                                                                                         |  
| d8b11a753f13936ec9d11414d31ab879 | http://ptpt.zhudazhanzuidiao.com/9013-1.0.5.16.apk                                                                                            |  
| c3ebc41cea3b6ef024ea882cf3b24d42 | http://ptpt.zhudazhanzuidiao.com/9013-1.0.5.16.apk                                                                                            |  
| 162a3d4572f5129bf0e88d5f7c45a84d | http://hd58r.zzxingda.cn/app/and/mimibo_14027.apk                                                                                             |  
| 162a3d4572f5129bf0e88d5f7c45a84d | http://wrs.mwtux.cn/apk/nyy/ss109.apk                                                                                                         |  
| 0480ddce61882b7633f128ba38af70ed | http://uk.neacgw.cn/apk/nyy/ss905.apk                                                                                                         |  
| 47c869f3338e1a5b6b7bdc6840999795 | http://vxr.bjjhlx.cn/apk/nyy/ss702.apk                                                                                                        |  
| 5a6f3e695ee94f601df82e2a2f472b87 | http://mdi.mwtux.cn/apk/nyy/ss926.apk                                                                                                         |  
| f72fcce5f4af011e8f358c672c8c57f5 | http://ik.whhlg.com.cn/apk/cmq/jf/cmq205.apk                                                                                                  |  
| 791d345adf90c5c5c2539e10ce444e46 | http://vxr.dongxinkeji.com.cn/apk/nyy/ss702.apk                                                                                               |  
| 3b9ac184bd7230ca6bccfb7bf07cc3ca | <http://ik.valid17.cn/apk/cmq/jf/cmq205.apk>                                                                                                  |  
| aa8f3a374b8492f974bd38d4b0fcd07c | [http://wkh.aordu.com/apk/nyy/ss876.apk](https://www.virustotal.com/gui/url/e0d9c20724467198e87e6cf005660d5154126f6249e68352830de8a6f090ac3d) |  
| 9be6afe31242945c8535be0375a56579 | http://az1.pc0359.cn/soft/c/com.shuaijiao.apk                                                                                                 |  
|                                  |                                                                                                                                               |  
| **C2**                            | **C2对应的IP**                                                                                                                                |  
| qf4in.01z9s.com                  | 47.91.4.125                                                                                                                                   |  
| jjna4.onp8p.com                  | 47.91.4.125                                                                                                                                   |  
| tt1dpn.vnitmtb.com               | 47.91.3.20                                                                                                                                    |  
| jxy69m.emtyfa.com                | 47.74.52.215                                                                                                                                  |  
| 4vhef6.8m149f.com                | 47.74.52.215                                                                                                                                  |  
| j07n4.od1dg.com                  | 47.91.2.173                                                                                                                                   |  
| zxluv.nu0sc.com                  | 47.91.2.173                                                                                                                                   |  
| xt0436.g80ggg.com                | 47.74.35.235                                                                                                                                  |  
| e4lhdz.0rqddg.com                | 47.74.35.235                                                                                                                                  |  
| yhk32.b4ril.com                  | 47.91.2.66                                                                                                                                    |  
| o108q.1a03i.com                  | 47.91.2.66                                                                                                                                    |  
| mfaqpe.k05yp2.com                | 47.91.2.173                                                                                                                                   |  
| pgwu2t.d2cxx4.com                | 47.91.11.215                                                                                                                                  |  
| umvhk.a1ant0.com                 | 47.74.47.207                                                                                                                                  |  
  
## 奇安信威胁情报中心  
  
奇安信威胁情报中心是北京奇安信科技有限公司（奇安信集团）旗下的威胁情报整合专业机构。该中心以业界领先的安全大数据资源为基础，基于奇安信长期积累的核心安全技术，依托亚太地区顶级的安全人才团队，通过强大的大数据能力，实现全网威胁情报的即时、全面、深入的整合与分析，为企业和机构提供安全管理与防护的网络威胁预警与情报。  
  
奇安信威胁情报中心对外服务平台网址为 ti.qianxin.com 服务平台以海量多维度网络空间安全数据为基础，为安全分析人员及各类企业用户提供基础数据的查询，攻击线索拓展，事件背景研判，攻击组织解析，研究报告下载等多种维度的威胁情报数据与威胁情报服务。  
  
![siduwenku.com 专注免费分享高质量文档](http://public.host.github5.com/media/aac0549900e532c5bdffe7e6fee175b7.jpg)  
  
## 红雨滴团队（RedDrip Team）  
  
奇安信旗下的高级威胁研究团队红雨滴（天眼实验室）,成立于2015年，持续运营奇安信威胁情报中心至今，专注于APT攻击类高级威胁的研究，是国内首个发布并命名“海莲花”（APT-C-00，OceanLotus）APT攻击团伙的安全研究团队，也是当前奇安信威胁情报中心的主力威胁分析技术支持团队。  
  
目前，红雨滴团队拥有数十人的专业分析师和相应的数据运营和平台开发人员，覆盖威胁情报运营的各个环节：公开情报收集、自有数据处理、恶意代码分析、网络流量解析、线索发现挖掘拓展、追踪溯源，实现安全事件分析的全流程运营。团队对外输出机读威胁情报数据支持奇安信自有和第三方的检测类安全产品，实现高效的威胁发现、损失评估及处置建议提供，同时也为公众和监管方输出事件和团伙层面的全面高级威胁分析报告。  
  
![siduwenku.com 专注免费分享高质量文档](http://public.host.github5.com/media/b1558686fc91b3bf51ba002ab86eb3a1.tiff)依托全球领先的安全大数据能力、多维度多来源的安全数据和专业分析师的丰富经验，红雨滴团队自2015年持续发现多个包括海莲花在内的APT团伙在中国境内的长期活动，并发布国内首个团伙层面的APT事件揭露报告，开创了国内APT攻击类高级威胁体系化揭露的先河，已经成为国家级网络攻防的焦点。  
  

# 延伸阅读 
 更多内容 可以[ 揭秘操控数百万Android手机的恶意营销插件. ](https://siduwenku.com/view/55036?f=2023)进一步学习

# 友情连接
[T-BSRS 008—2020 核与辐射应急数据交换标准 第1部分：体系结构和公共基础数据.pdf](http://github5.com/view/70946?f=new)

[T-GDVIA 037—2022 桑芽菜现代电商物流保鲜技术规程.pdf](http://github5.com/view/81626?f=new)

[DB11-T 1456-2017 热电联产（燃气）单位产品能源消耗限额 北京市.pdf](http://github5.com/view/42982?f=new)
