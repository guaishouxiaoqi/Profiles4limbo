![Quantumult x for limbopro][1]
![Quantumult x for limbopro-newest][2]

⬆️ 新旧版本界面；

# Profiles4limbo
毒奶预配置文件（Quantumult X）懒人一键配置，在你进行下一步操作之前请耐心把本文档看完以免造成不必要的麻烦，包含但不限于有可能存在的报错及规避方法，如何删除 ♻️故障切换 策略组下的无用节点（删除该无用节点的同时务必新增2个以上节点才能进行保存）；

# 及时收讯与反馈交流
0. 关于本预配置文件在使用过程中如有问题请务必优先参考本文档操作步骤和FAQ部分自行尝试解决，更多问题或建议请加入我们的电报群组；
1. [TG 电报频道](https://t.me/limboprossr)；
2. [TG 电报群组](https://t.me/Adblock4limbo)；
3. [Twitter](https://twitter.com/limboprossr)；

# 说明

## 历史更新说明 

### 12.27.2020 更新说明

Tiktok 最新版 v.18.2.1 可以解锁啦！记得备份啊笨蛋！个性化解锁参考 [如何使用Quantumult X解锁 TikTok 区域限制（免拔卡）](https://limbopro.xyz/archives/11773.html)

### 11.13.2020 更新说明

更新了分流规则至神机规则最新库；

### 10.25.2020 更新说明

<details>
<summary>展开查看</summary>

1. 更新 预配置文件中分流规则至 **神机规则（更新中）**；
2. 更新 **本预配置文件所引用到的仓库**；
3. 新增毒奶去广告 [Rewrite] 跟 [filter]；参阅 https://t.me/limboprossr/1952 配置；可去除[奈菲影视](https://www.nfmovies.com/) /[低端影视](https://ddrk.me/)/[Jable.tv](https://jable.tv/)/[netflav](https://netflav.com)/[片库网](https://m.pianku.me/)/[嘀哩哩网站](https://www.dililitv.com/) 上的广告（内页广告以及片头广告）。
</details>


## 毒奶预配置文件说明

0. 利用 Quantumult X 自带的 [配置文件] - [下载] 功能对 Quantumult X 各个模块进行预配置；
1. 包括但不限于[分流]/[重写]；
2. 利用 NobyDa 贡献的脚本解锁🔓各项事务，VSCO，~~Termius~~，网易蜗牛读书会员等；
3. **Surge/Clash** 用户可使用由毒奶提供的 订阅转换 API，亦能获得相同的效果；https://limbopro.xyz/archives/subconverter.html

## 本预配置文件所引用到的仓库说明

<details>
<summary>展开查看</summary>

0. 在此毒奶对大家的付出表示感谢
1. [NobyDa](https://github.com/NobyDa/Script/tree/master) 脚本仓库（*如删库可替换 NobyDa 为 limbopro，其他同理）
2. [NobyDa-AD](https://github.com/NobyDa/ND-AD) 野比去广告分流；（10w+）
2. [ConnersHua](https://github.com/ConnersHua/Profiles/tree/master) 神机规则（停止更新）
3. [DivineEngine](https://github.com/DivineEngine/Profiles/tree/master) 神机规则（更新中），包含 `YouTube APP`去广告/`Tiktok` 解锁的重写，请自行查看；
3. [limbopro](https://github.com/limbopro/Profiles/tree/master/limbopro) 机场专线
4. [Qure](https://github.com/Koolson/Qure/tree/master/IconSet) 开源图标
5. [chavyleung](https://github.com/chavyleung/scripts) 签到脚本

</details>

## 关于策略组及分流的说明

<details>
  <summary>展开查看</summary>

⚠️ 本预配置文件默认8个策略，如上方**预览图**中所示；按以下 **具体操作** 操作完毕后即可在 Quantumult X 主界面看见。

- **故障切换**：该策略自动检测组内节点可用情况（surge 会切换选中最低延迟节点）；；
- **机场专线**：主流机场域名分流规则，例如 N3RO ，你可使其请求走代理，直连等；
- **社交媒体**：国外社交媒体，如Twitter/Facebook/Instagram/Telegram 等，**流量消耗小，但需要稳定**；
- **苹果服务**：苹果服务相关分流规则；
- **Netflix**：鉴于大家喜欢看 Netflix；
- **其他国外流媒体**：如油管，P站等一切你可以想得到国外流媒体，**流量消耗大**；
- **广告拦截**：默认选择 `Reject`，广告拦截可能会造成某些错误🙅，届时 将 **广告拦截** 的 **策略偏好** 修改为 PROXY 或 Direct 即可；
- **Final**： 排除以上已知的分流规则的其他未知；

</details>

# 具体操作

📢 如果你有多个机场订阅，则可参考 本文档的 **FAQ** 部分说明进行备份； 

## 第一步 下载毒奶预配置文件

1. 复制 https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/full.conf 预配置文件链接（大家也可以在浏览器内打开该预配置文件链接以查看具体配置详情，好做进一步的理解）；
2. 进入 QuantumultX ，点击右下角 [三菱按钮]
3. 找到 [配置文件] 模块下的 [下载] 点击
4. 粘贴 刚刚复制的配置 [链接]，点击 右上角 [确定] 按钮
5. 确认，届时 QuantumultX 已添加 8个策略

⚠️ Quantumult X 最新版本中在你还没有**订阅机场节点**（即第三步完成）前，APP主界面可能不会直接出现这8个策略；（02.19.2021）

## 第二步 生成并配置证书
0. 如果再此之前已经生成并信任证书则 **生成并配置证书**这一步可选择忽略；
1. 进入 QuantumultX ，点击右下角 [三菱按钮]
2. 找到 [MitM] 模块 - 生成并配置证书📄 

- 进入QuantumultX，点击页面右下角三菱`按钮`，找到`MinM`模块，点击`生成证书`，提示生成成功，点击`安装证书`此时会跳转至` Safari`，提示`此网站...下载一个配置描述文件。您要允许吗？`，点击`允许`，网页提示`已下载描述文件`；
- 进入 iOS 系统`设置`-` 通用`-`描述文件`-`已下载的描述文件`-选中，并安装，输入密码...完成描述文件安装；
- 进入 iOS 系统`设置`-` 通用`-`关于本机`-`证书信任设置`-`针对根证书启用完全信任`-选中刚刚安装的并启用即可；

3. 找到 [重写] 模块 - 开启按钮 🔘
4. 找到 [MitM] 模块 - 开启按钮 🔘

## 第三步 订阅机场节点并为各个策略添加或删除节点
![Quantumult X PROXY/POLICY/延迟/节点可用性测试/操作界面认识/名称编辑/背景编辑.png][3]

1. 订阅你的机场节点；（📢如果对Quantumult X 操作不熟悉，请不要删除名为“无用节点”的节点订阅链接；）
2. 一切就绪后进入 QuantumultX 主界面，长按各个 **策略组对应的图标或策略组名字**（如`♻️故障切换`/`🛬机场专线`..）就可以为该策略组添加+/或删除-不需要的节点了；
3. 注意！📢若策略下如`故障切换`，出现有红色感叹号❕标注的节点务必删除，并添加2个以上节点后保持；

## 第四步 为机场专线分流选择策略偏好
1. 进入QuantumultX，在主界面找到名为`🛬机场专线`的`自定义策略`，点击展开可看到`其他国外流媒体`/`Proxy`/`故障切换`/`DIRECT`四个选项；（如果你的机场订阅无法更新，可依次选择 `DIRECT`/`PROXY`后再进行机场订阅更新，DIRECT意为着直连，不通过代理更新你的机场订阅；） 
2. 如果你的机场订阅仍然无法更新，在主界面找到名为`🐟Final`的`自定义策略`，点击展开可看到`其他国外流媒体`/`Proxy`/`故障切换`/`DIRECT`四个选项；（如果你的机场订阅无法更新，可依次选择 `DIRECT`/`PROXY`后再进行机场订阅更新，DIRECT意为着直连，不通过代理更新你的机场订阅；） 
3. 更多疑问请查看  **FAQ** 部分；

# 出现错误及解决 Faq 

## 未知错误 - 未知策略或节点
![未知错误 - 未知策略或节点解决办法.png][5]

## 网络活动
![QuantumultX - 网络活动.png][4]

在反馈问题前，请多看看 **网络活动日志模块**（QuantumultX 主界面 **橘红色** 的日记本标识，里面📝了你的各个网络请求）；多熟悉一下 QuantumultX 操作界面，可能帮助你解决很多常见问题。

 1. **Tiktok 免拔卡解锁**：https://limbopro.xyz/archives/3629.html
 2. **加入毒奶去广告计划**：https://limbopro.xyz/archives/12904.html
 3. **解析器过滤节点以及regex**（**新**）**参数的用法**：https://limbopro.xyz/archives/11131.html

## 备份你的机场订阅链接🔗
1. 进入 QuantumultX ，点击右下角 [三菱按钮]
2. 找到 [配置文件] 模块 - 点击 [编辑] - 找到 [server_remote] 
3. 复制 [server_remote] 下方的机场订阅链接🔗 存到某处备用
4. 届时 恢复时 重新在 [server_remote] 下方 粘贴即可

## 使用毒奶预配置文件后的一些检查
1. 如果出现错误提示，不要慌
2. 进入 QuantumultX 主界面 - 各个图标点一下 看一下
3. 熟悉一下

## Faq 

1.如果你是YouTube 会员，则应该进 `重写`- `引用` - 找到并禁用 `DivineEngine (Youtube AdsBlock)`

## 及时更新
*保持更新。

1. [分流] - [引用] 更新
2. [重写] - [引用] 更新

# 最后 BTW
因为这个配置文件也是我自用的，会保持更新，但一般无太大问题不建议大家每次跟随更新。

## 进阶玩法
https://limbopro.xyz/archives/3846.html

## 关注频道
https://t.me/limboprossr

[1]: https://raw.githubusercontent.com/limbopro/Profiles/master/limbopro/Gift/Without/unzip/QuantumultX4limbopro.PNG
[2]: https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/Quantumult%20X%20v1.0.18.PNG
[3]: https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/Quantumult%20X%20%E4%B8%BB%E9%A1%B5%E4%BB%8B%E7%BB%8D.png
[4]: https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/%E6%97%A5%E5%BF%97.png
[5]: https://raw.githubusercontent.com/limbopro/Profiles4limbo/main/%E2%99%BB%EF%B8%8F%20%E6%95%85%E9%9A%9C%E5%88%87%E6%8D%A2.png


