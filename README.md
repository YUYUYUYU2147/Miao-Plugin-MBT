![](https://files.seeusercontent.com/2026/10/26/1paE/Generated-Image-October-26-2026-.jpg)

  
图库是 Yunzai 的插件角色面板图资源补充，涵盖了**原神&星铁&绝区零&鸣潮**的面板图资源，现在已经拥有六仓分流的存储架构并且持续的优化使用体验和面板图视觉设计，项目创建于2023年10月左右吧，咕咕牛希望能够提供更优质的面板图资源，留学移民可进群交流：<a href="https://qm.qq.com/q/cyXMqRBzY6" target="_blank" style="text-decoration: none;">
  <button style="
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: white;
    background: linear-gradient(to right, #00aaff, #0077ff);
    border: none;
    border-radius: 8px;
    cursor: pointer;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    transition: background 0.3s ease;
  " onmouseover="this.style.background='linear-gradient(to right, #0099dd, #0055dd)'"
     onmouseout="this.style.background='linear-gradient(to right, #00aaff, #0077ff)'">
    💬 留学移民交流群
  </button>
</a>；

## 内容净化与过滤

> [!WARNING]
> 为应对潜在的封号威胁建议根据自身需求配置，此功能是贯穿图库的核心优先级最高请着重考虑！

| 等级 | 效果         | 说明                                              |
|:----:|:-------------|:--------------------------------------------------|
| 0    | 无过滤       | 显示所有面板图，含敏感内容 ( 轻微露点占比0.02% )        |
| 1    | 常规净化     | 过滤全部 Rx18，保留低敏感的 Px18 内容 ( 包含了暗示、非正常行为 )    |
| 2    | 最高净化     | 严格过滤所有敏感内容（含 Rx18 + Px18）            |

> Tips: 面板图内容的展示优先级： 远程封禁 > 净化等级 > 封禁一二级标签 > 封禁单张

此外，咕咕牛还支持元数据级的面板图封禁，配合以下指令可独立管理图片类型开关：
- #咕咕牛封禁 / 解禁 ```木偶Gu1``` (角色名可不打Gu)
- #咕咕牛设置 Ai图 / 彩蛋图 / 横屏图 ```启|禁用``` (一级标签)
> Tips: 二级标签需要通过 '#咕咕牛查看' 了解有哪些标签,封禁会导致拥有该标签的图片被自动连坐封禁
- #咕咕牛封禁 / 解禁 ```黑丝/白丝/比基尼``` (二级标签) 

## 社区面板图库

> [!TIP]
> 新的部署方案将会在 v5.3.0 图库管理器实装，届时会通过动态API缓解存储占用问题

| 作者 | 仓库地址 | 说明 | 预估体积 |
| :--- | :--- | :--- | :--- |
| 何日见 | [查看仓库](https://github.com/herijian1/characterpic1) | 喵喵插件原神星铁高质量面板图 | 650MB + |
| 夜 | [查看仓库](https://github.com/ye3011/normal-character) | 喵喵插件面板图 | 9.5GB + |
| 阿修 | [查看仓库](https://github.com/AxiuCN/miao-plugin-ProfileImg) | Yunzai 的原神与星铁面板图图库 | 700MB + |

一键部署命令： 
- #咕咕牛安装何日见
- #咕咕牛安装夜
- #咕咕牛安装阿修

## CowStudio 内容管理工作站

| 功能 | 说明 |
|---|---|
| 图库管理 Web 版 | 提供基于 Web 操作的图库管理功能 |
| Yunzai 管理 | 支持 Yunzai 插件、消息及面板图管理 |
| 数字资产可视化 | 支持咕咕牛图库数字资产的可视化展示 |
| 群用户交互优化 | 优化群用户交互体验 |

输入 `#咕咕牛登录` 获取访问链接，在群聊中发送则会隐藏公网IP

<details>
<summary><strong>CowStudio 内容管理工作站界面截图</strong></summary>
<img src="https://files.seeusercontent.com/2026/09/04/cxP9/download.png" alt="download.png" />
<img src="https://files.seeusercontent.com/2026/09/04/pZ8a/download.png" alt="download.png" />
</details>

## 面板图侧栏水印说明

在保障 **作者** 数字图像版权、咕咕牛图库权益的前提下面板图都会带有标识信息水印和暗水印，不影响正常使用且在渲染后完全看不到该水印介意请勿安装！

<p align="center">
  <img src="./gs-character/桑多涅/桑多涅Gu8.webp" width="100%">
</p>

## 图库的安装方式

在 Yunzai 根目录打开终端执行以下命令安装管理器并通过管理器安装图库：

> [!TIP]
> 部署后输入 **#咕咕牛帮助** 查看命令，输入 **#下载咕咕牛** 安装图库自动启用。你至少需要准备 Nodejs 22 版本以上，否则会报错。<br>

```bash
curl -o "./plugins/example/咕咕牛图库管理器.js" -L "https://cdn.jsdelivr.net/gh/GuGuNiu/Miao-Plugin-MBT@main/咕咕牛图库管理器.js"
````

### ⚠️ 使用须知 · 请务必仔细阅读

- **图库使用付费的商业资源严禁用于任何商业用途**，**商业资源**仅用于展示用途且仓库持有者不拥有其版权**后续使用或传播行为与本项目无关**。如认为图库存在侵权行为请在 issues 建帖联系删除。
- **Paid commercial assets included in the gallery must not be used for any commercial purposes.** These assets are provided for display purposes only, and the repository owner does not hold the copyright to them. **Any subsequent use or redistribution of these assets is unrelated to this project.** If you believe the gallery contains copyright-infringing content, please open an issue to request its removal.

---

## 项目透明墙

> 以下对"数字资产所有者"，"面板图二次创作使用来源“，"图片原创者"，"数字影像所有者"统称为**原创者**

<table border="1" style="width: 100%; table-layout: fixed;">
  <tr>
    <th>模块/功能</th> 
    <th>具体说明</th>
  </tr>
  <tr>
    <td>远程封禁</td> 
    <td><strong>远程封禁模块/功能</strong>仅用于保障<strong>“原创者“</strong>的版权追溯，<br>
    <strong>远程封禁模块/功能</strong>不涉及任何 <strong>后门</strong>，咕咕牛仅作为协助<strong>暂停图像分发</strong>，<br>
    任何行为应遵循<strong>“原创者“</strong>当地法律，咕咕牛不承担因此产生的任何<strong>法律责任</strong>。</td> 
  </tr>
  
  <tr>
    <td style="white-space: nowrap;">树复制</td> 
    <td>以下对该模块/功能简称<strong>"资源同步":</strong> <br>
     <strong>资源同步模块/功能</strong>仅用于保障<strong>“原创者“</strong>的版权追溯清理遗留在用户本地的图片文件，<br>
  </tr>

</table>


## 其它仓库

<div align="center">
  <a href="https://github.com/GuGuNiu/Miao-Plugin-MBT-2">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=GuGuNiu&repo=Miao-Plugin-MBT-2&theme=default" width="32%" alt="Miao-Plugin-MBT-2" />
  </a>
  <a href="https://github.com/GuGuNiu/Miao-Plugin-MBT-3">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=GuGuNiu&repo=Miao-Plugin-MBT-3&theme=default" width="32%" alt="Miao-Plugin-MBT-3" />
  </a>
  <a href="https://github.com/GuGuNiu/Miao-Plugin-MBT-4">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=GuGuNiu&repo=Miao-Plugin-MBT-4&theme=default" width="32%" alt="Miao-Plugin-MBT-4" />
  </a>
  <a href="https://github.com/Siluluna/Genshin-CR-Repos">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Siluluna&repo=Genshin-CR-Repos&theme=default" width="32%" alt="Genshin-CR-Repos" />
  </a>
  <a href="https://github.com/Siluluna/StarRail-CR-Repos">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Siluluna&repo=StarRail-CR-Repos&theme=default" width="32%" alt="StarRail-CR-Repos" />
  </a>
</div>

<p align="center">
  <a href="https://github.com/GuGuNiu/Miao-Plugin-MBT">
    <img src="https://count.getloli.com/get/@GuGuNiu-MiaoPluginMBT?theme=moebooru" alt="Visitor Count" />
  </a>
</p>
