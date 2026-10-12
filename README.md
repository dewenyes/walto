# Walto

**Turn any image into a wallpaper.** 让每一张图片，都成为好壁纸。

Walto is a bilingual (Chinese / English), tool-neutral Agent Skill for turning screenshots, photographs, illustrations, and creative briefs into wallpapers.

Walto 是一款兼容中英文的通用 Agent Skill，可将截图、照片、插画或文字创意制作成壁纸。

## Capabilities / 功能

- Screenshot restoration / 截图还原与去除界面元素
- Faithful outpainting and reframing / 忠实扩图与构图适配
- Portrait and landscape wallpapers / 横竖屏壁纸
- Targeted edits / 局部编辑
- Style-consistent variations and original creation / 同风格衍生与原创

**Orientation / 画面方向：** If the user has not specified portrait or landscape, the agent must ask before generating. 若未指定横屏或竖屏，生成前必须先询问。

## Install / 安装

### Skills CLI

```bash
npx skills add dewenyes/walto --skill walto
```

Select your agent and installation scope when prompted. 按提示选择工具与安装范围。

### ZIP / 安装包

Download [walto-v1.0.0.zip](https://github.com/dewenyes/walto/releases/download/v1.0.0/walto-v1.0.0.zip), then import the complete ZIP into an agent that supports Skill uploads, or extract and copy the `walto` folder into its Skills directory.

下载完整 ZIP，在支持 Skill 上传的工具中导入，或解压后将 `walto` 文件夹复制到对应技能目录。请保留随附的 LICENSE 和 README。

### Qoder

For Qoder IDE / CLI:

```bash
npx skills add dewenyes/walto --skill walto -a qoder
```

For the Qoder desktop app, use Extensions → Skills → Add Skills → Upload Skill and select the ZIP. QoderWork also supports installing from a GitHub link. Interfaces differ between Qoder editions; follow the documentation for your edition.

Qoder 桌面版可通过扩展 → 技能 → 添加技能 → 上传 Skill 导入 ZIP。QoderWork 也支持提供 GitHub 链接后要求安装。不同版本界面可能不同，请按所用版本说明操作。

## Try Walto / 开始使用

Upload an image and ask: “Use Walto to turn this image into a portrait wallpaper, preserving the subject and style.”

上传图片后说：“使用 Walto，把这张图片制作成竖屏壁纸，保留主体和原图风格。”横屏同样支持。

Installing Walto provides instructions, not a bundled image model or API credits. Actual image generation depends on your agent's tools and any provider you configure.

安装 Walto 提供的是工作流程，不包含图像模型或 API 额度。实际生成能力取决于宿主工具和你配置的供应商。

Documentation: [Skills CLI](https://skills.sh/docs) · [Qoder Skills](https://docs.qoder.com/qoder/skills) · [Qoder IDE Skills](https://docs.qoder.com/extensions/skills)


## Requirements / 使用条件

The agent must have access to an image generation or editing tool to produce images. Without one, Walto can only provide guidance or prompts. 生成实际图片需要运行环境具备图像生成或编辑工具，否则只能提供方案或提示词。

## License / 许可

Walto License 1.0 — source-available, free to use and create, not for resale. See [LICENSE](LICENSE) for the complete terms; the Chinese text governs.

Walto 采用自定义授权，属于源码公开项目，并非 OSI 定义的开源项目。完整条款见 [LICENSE](LICENSE)，以中文条款为准。

- 免费使用、研究和修改；免费公开分发须保留版权、许可证、Walto 来源署名及原项目链接，并注明修改
- 禁止出售 Walto 或修改版、收费打包分发，以及将其用于收费的衍生 App、订阅或自动化生成服务；此类用途须另行取得权利人授权
- 使用 Walto 制作的壁纸可免费分享、出售或用于商业设计，无须署名 Walto；仍须遵守素材、肖像及模型供应商的相关要求

Attribution / 来源署名：Based on Walto — https://github.com/dewenyes/walto
