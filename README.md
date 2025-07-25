# XDUCraft NBS
## 介绍
由于OpenNoteBlockStudio开发组声明不对Disc Jockey/Notebot建立官方支持曲库，并且为便利XDUCraft的各位同学快乐游玩而建立的专用NBS曲库。其中并非所有资源都由XDUCraft社团制作，不少资源来自于网络。这也并非是我们特定的曲库，欢迎任何同学/同僚的加入。

## 目录

## 使用说明
1. **安装模组**
   
   **[DiscJockey](https://www.curseforge.com/minecraft/mc-mods/disc-jockey) + (可选，用于调节Disc Jockey的相关配置)[ModMenu](https://modrinth.com/mod/modmenu)**</br>
   或 **[MeteorClient](https://meteorclient.com/)** 和 **FutureClient** </br>

   >注意Meteor端和Future端是挂端。<br>
   >Future端是付费端，请*自行解决使用问题*，本仓库不直接提供诸如Crack版的副本。<br> 

2. **获取NBS文件**
   
   **如果你想直接下载全部歌曲**。
   点击右上角“克隆/下载”按钮，选择“下载ZIP”或利用git运行命令行指令。

   ```bash
   git clone https://gitee.com/ayasapphire/xducraft-nbs.git
   ```

   **如果你只对部分歌曲感兴趣**
   点击进入相应目录，选择你想要的歌曲文件NBS，点击下载即可。

3. **安装歌曲**
   对于Disc Jockey，将歌曲拖入游戏对应菜单窗口或如下目录
   >.minecraft/config/discjockey/songs/

   对于Meteor端，将歌曲拖入如下目录
   >.minecraft/meteor-client/notebot/

## 参与贡献
如果你也想参与到这个NBS库的编写（编曲），为这个库做出自己的贡献，我们随时欢迎。详情可以联系邮箱ayasapphire@qq.com或者在[XDUCraft群](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=GF4Ej90Dz5BJpIEGFs4DjkHIouVGD0hR&authKey=hEzyZX6lIOTEk4jwmvZDSQZCD2MV24xiIexe%2BaI9yM9Meo%2Bu0P9TvBukIDFKH5hT&noverify=0&group_code=684941112)内联系管理员。

## 声明

### 资源中立性声明

本资源库仅作为音乐文件共享平台，不代表维护者支持或认可任何原创作者的政治倾向、立场及观点。使用者应对内容自行判断。</br>

### 版权响应

所有文件版权归属原作者及权利人。收到版权方正式通知后，我们将在48小时内移除争议内容。侵权通知请提交至：ayasapphire@qq.com</br>

### 无担保声明

资源按"现状"提供，维护者不承诺：

- 音色与游戏版本的永久兼容性
- 文件完全无版权争议
- 资源存储的永久可用性

### 使用者责任

使用者需确保：

- 遵守服务器插件政策（如禁止Notebot）
- 不将资源用于商业盈利

### 免责条款

维护者不对以下情况：

- 因使用资源导致的账号封禁
- 文件下载引发的系统安全问题

### 协议变更权

我们保留随时更新本声明的权利，恕不另行通知。</br>

## 多说几句

请注意，本曲库中的所有 .nbs 文件均基于**原版 Minecraft 音符盒的音域，音色平衡以及 Notebot 无音量控制**等限制进行编排。为了适应这些限制，编曲过程中会有大量妥协，包括但不限于**和弦转位的不精确、音色替换，甚至舍弃副旋律、琶音、音效或鼓点声部**。尽管这些文件在理论上可用于红石音乐，但在实际使用前，请务必考虑并自查以下要点：

1. 生存模式建造
> 红石信号以 2 游戏刻（约 0.1 秒）为一个刻进行触发。请选用 100 BPM、150 BPM、200 BPM 或它们的倍数/近似值, 否则无法实现。

2. 创造模式建造

> 您**不受notebot的无音量限制**：编曲中通过调整音符盒摆放密度来替代部分声部音量，但你可以选择控制距离来实现音部音量平衡而非密度；还可采用[**立体声**](https://www.bilibili.com/video/BV1Mw91YmEgJ/)布局等高级手法。

> 您**可以使用自定义资源包**：可加载 [**NoteBetter**](https://github.com/chsbuffer/NoteBetter) 等资源包，打破原版音域限制，更可以将音符盒替换为**其他任意乐器音源**。

> 您**可以使用命令方块**：可利用 **/playsound** 直接播放音源文件，实现类似 MIDI 播放器的效果。

3. 如果您在评估以上方案后，仍坚持 **“仅/tickrate 更变的原教旨主义红石音乐”** 架构，也可一键生成本曲库中的 .nbs 文件，但这**并不会让您真正掌握红石音乐的创作技巧**。