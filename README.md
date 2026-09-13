# A-Life-Archive

个人作品与人生档案管理工作台，在一个界面中集中整理书籍、电影、音乐、旅行、游戏、自定义作品、章节资料、统计与时间轴。

## 主要功能

- 通过类型、分组和作品卡片管理个人收藏与长期项目，支持普通、封面和图文三种视图。
- 为每个作品管理 Markdown、Canvas 和 Excalidraw 章节文件，并提供对应的详情、摘要和编辑入口。
- 支持作品与章节的创建、编辑、搜索、筛选、排序、折叠、拖动、置顶、导入和安全删除。
- 提供全局索引、标签与属性筛选，以及总统计、年统计、月统计和可拖动时间轴。
- 四个分区之间静默联动，修改作品属性后同步更新相关卡片、索引、统计和时间轴。
- 支持亮色、深色和小岛主题，并提供 Banner、专注模式和多种界面状态记忆。
- 使用 Vault 内的 Markdown、JSON 和相关资源文件保存数据，便于随 Vault 备份与同步。

## 付费与激活

A-Life-Archive 是需要购买许可证并激活后使用完整功能的付费插件。未激活时仅显示 Banner 和激活区域，也可以进入插件设置完成激活。

激活码请通过作者的正式销售或联系渠道获取：

- [购买 A-Life-Archive 激活码](https://wzyp.cn/shop/NIAR958A)
- QQ群：603045364
- 微信：VinVinVin444
- [Bilibili](https://space.bilibili.com/3493128231193555)
- [小红书](https://xhslink.cn/m/8ZWjZpJc6sK)
- [抖音](https://v.douyin.com/bqTGipbnW_8/)

## 网络访问

A-Life-Archive 只在下列场景访问网络：

1. 激活许可证，以及在离线许可进入续签窗口、过期恢复、可信时间异常或用户主动验证时连接授权服务器。
2. 用户主动通过 URL 下载作品封面时，访问对应的图片服务。
3. 用户配置外部 Banner 图片时，加载对应的图片地址。
4. 用户主动使用外部搜索功能时，在浏览器中打开所选搜索服务。

授权服务可能接收激活或验证所必需的数据类别：激活码（仅激活时）、产品代码、匿名设备 ID、设备名称与平台信息，以及续签时的离线许可证。插件不会把激活码写入设置或日志。

## 隐私

- 无客户端遥测。
- 无使用行为分析。
- 无广告跟踪。
- 不出售用户数据。

完整说明见 [PRIVACY.md](./PRIVACY.md)。

## 数据与备份

作品、章节、时间轴、资源和插件配置主要保存在当前 Vault 的 `A_LifeArchive_Data` 目录。插件会按需读取共享目录 `A_Shared_Data` 中已经存在的公共配置。离线许可证保存在当前 Vault 的插件配置数据中；匿名设备 ID 保存在当前 Vault 配置目录下的 `a-license/device.json`。

备份整个 Vault 时，上述业务数据会一并备份。跨设备同步插件配置目录时，请注意每个授权设备仍受许可证设备数量限制。通过插件删除受管理文件时，文件会移动到 Obsidian 的 `.trash` 目录。

## 安装与更新

正式上架后，请通过 Obsidian Community Plugin Directory 安装和更新。不要从非官方来源下载修改过的构建文件。

## Source and review

A-Life-Archive is a paid, license-activated plugin. Its complete TypeScript source code is maintained in a private repository. Release builds are submitted to the Obsidian Community Directory review and scanning process.

The plugin connects to its licensing service only for activation and periodic license validation. It sends the minimum license-related data described above. Cover downloads, remote Banner images, and external searches occur only after user action or configuration. A-Life-Archive contains no client telemetry, usage analytics, or advertising trackers.

## Third-party software

Third-party notices are available in [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md).

## Support

作者：全平台-岛民Vin。问题反馈与购买咨询可通过上述作者渠道联系，也可以前往[公开发布仓库 Issues](https://github.com/VinVinVin444/A-Life-Archive-Releases/issues)。

## License

A-Life-Archive is proprietary commercial software distributed under the terms in [LICENSE](./LICENSE). Third-party components remain governed by their respective licenses.
