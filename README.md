## 懒人米表
> 懒人不生产代码，只是代码的搬运工，感谢各位大佬提供的思路。

### 灵感来源
- 闲逛`Github`发现了垃圾佬的[简易米表](https://github.com/naiba/domain-portfolio)，觉得这种借助`Github Pages`的方式很不错，同时又收到了[NGY](http://n.gy)分享的他的米表源码，后来发现应该来自[巧克力-非主流](https://mb.admin.pet/)，于是将以上结合了一下。又加入了自己的一些设计元素，经过了自己的一些修改和调整，于是[懒人米表](http://dai.wiki)诞生了。最后更进一步，也支持`Vercel`部署了。

### 使用方式
> 不会使用`Github`的朋友，可以先通读详细步骤里的内容。
- 使用 **Github Pages** 部署
    - `fork`本项目到自己仓库，拉取仓库到本地。
    - 更改一下`img`文件夹里的图片和`_config.yaml`配置文件，并将更新后的文件送到仓库。
    - 最后开启`Github Pages`并绑定自定义域名，过一会就会自动生效。
- 使用 **Vercel** 部署（**推荐**）
    [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/newbill/domain-list)
    - 去 [Vercel](https://vercel.com/) 创建个`Vercel`账号，推荐选择`Github`登录。
    - 点击上面的快速部署按钮后，然后去`Github`拉取`Vercel`为我们创建的仓库。
    - 更改一下`img`文件夹里的图片和`_config.yaml`配置文件，并将更新后的文件送到仓库。
    - 喝杯咖啡，`Vercel`会自动拉取并部署，过一会就会生效了。

### 详细步骤（选看）
> 考虑到有些用到这个米表的朋友不太会用`Github`和`Git`，所以我就写的具体一点，会使用的就不用往下阅读啦。

#### a. 装个软件
- 版本控制工具：`fork`，一款可视化执行`Git`命令的工具，自带`Git`环境，可以降低新手操作`Github`的门槛，免去本地安装配置`Git`和学习一些繁琐的`Git`命令。这款软件全平台都有，直接去官网下载就可以，免费。[下载传送门](https://Git-fork.com/)
- 说明：其实`Github`也可以直接修改代码和图片，但是感觉不太方便，长期更新米表的话，还是拉到本地吧。

#### b. fork 项目
- `fork`完毕后你自己的`Github`里就有一个一样的仓库，然后找到下图位置复制仓库链接。
  ![2207091933571657374373763.png](http://oss.dai.im/img/202207/220709193357-1657374373763.png)
- 打开刚刚安装的fork工具，`clone`远程仓库到本地。
  ![2207091936371657374431410.png](http://oss.dai.im/img/202207/220709193637-1657374431410.png)
- 然后修改本地仓库的`img`文件夹里的图片和`_config.yaml`配置文件，配置规则见配置文件。
- 修改完毕之后，`stage`所有想要更新到`Github`仓库的文件，然后写上注释点击`commit`。
  ![2207091936381657374906819.png](http://oss.dai.im/img/202207/220709193638-1657374906819.png)
- `commit`成功之后，最后一步就是推送`push`到远程仓库也就是`Github`，点击`fork`快捷操作栏的`push`箭头即可。
- 这时候去刷新`Github`，会发现仓库文件已经更新了，如此我们就完成了更新并推送成功。

#### c. 开启 Github Pages，并绑定域名（可选）
- 如图，在仓库的`Setting`里找到`Pages`，然后开启就完事了。
  ![2207091943541657375018014.png](http://oss.dai.im/img/202207/220709194354-1657375018014.png)
- 接下来，喝杯咖啡，剩下的活就交给`Github`自动去部署，稍等一会，看到`Actions`里面的任务执行完毕或者仓库首页如图所示，说明已经成功了，至此教程结束。
  ![2207092137091657375055033.png](http://oss.dai.im/img/202207/220709213709-1657375055033.png)

#### d. Vercel 相关设置（可选）
- `Vercel -> Setting -> Domains`：绑定自定义域名
- `Vercel -> Setting -> Serverless Function`：选择部署的地区，一般选香港国内访问最佳

#### e. 更新米表
- 以后如果要更新页面信息，我们只需要更改本地的配置文件，然后再通过`fork`软件将更新的文件推送到`Github`仓库就可以了，`Github`或者`Vercel`会检测到仓库更新，自动帮我们去更新米表页面。
- 对于这种数据不敏感，无需后台无需数据库的静态页面，只需要改变提取到配置文件的信息就可以完成更新的方式也是最简单和划算的。

#### f. 其他说明
- 可以同时开启`Github Pages`和`Vercel`，没有影响，绑定不同域名就可以了。
- 开放的公共配置支持小标签和纯文本两种效果，请自行选择，同时也可以自定义四种颜色随意搭配。自认为配置文件里抽取的配置可以满足大多数人的要求，如有不满，可以自行更改样式和页面文件。
- 如果你熟悉`Github`或者`Gitee`的话，也可以下载本仓库的所有文件，然后自行部署。代码也可以随意修改，但还是希望可以给个`Star`表示鼓励。祝操作顺利，玩得愉快！

### 两种效果
- [小标签](http://dai.wiki)
- [纯文本](http://mibiao.vercel.app)

### License
[MIT](https://github.com/newbill/domain-list/blob/main/LICENSE)
© 2022 - present [NEWBILL](https://github.com/newbill)