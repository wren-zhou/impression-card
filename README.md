# impression-card

An agent skill that creates richly detailed, romantic European storybook illustrations with Monet-inspired light, colour and brushwork.

一个 AI 智能体技能（agent skill）：生成细节丰富的浪漫欧洲故事书插画，融合莫奈式的光影、色彩与笔触。

---

## What it does · 它能做什么

- One standalone, full-bleed illustration per request (vertical 2:3 by default).
- Three-plane depth: flowers and foliage in the foreground, streets and architecture in the middle ground, rooftops and sky in the background, all overlapping naturally.
- Architecture stays crisp and readable; flowers, foliage, sky and reflections get Monet's broken colour, coloured shadows and soft atmospheric light.
- Strong on Parisian scenes: Haussmann façades, mansard roofs, iron balconies, café terraces.

&nbsp;

- 每次生成一张完整的独立插画，默认 2:3 竖版，铺满画面。
- 三层景深：前景是花草枝叶，中景是街道和建筑，远景是屋顶和天空，彼此自然交叠。
- 建筑结构清晰精致；花草、天空和倒影用莫奈式的碎色笔触、彩色阴影和柔和的大气光。
- 尤其擅长巴黎街景：奥斯曼式立面、复折式屋顶、铁艺阳台、咖啡馆露台。

## Install · 安装

Designed for **Codex**, which can generate images. Clone it into your personal skills folder:

为 **Codex** 设计（Codex 自带生图能力）。克隆到个人 skills 文件夹即可：

```bash
git clone https://github.com/wren-zhou/impression-card.git ~/.agents/skills/impression-card
```

Codex usually picks up new skills automatically; restart it if the skill does not appear.

Codex 一般会自动识别新技能；如果没出现，重启一下。

Other agents that follow the agent skills standard can use it too, as long as they have an image generation tool. Copy the folder into that agent's skills directory.

其他支持 agent skills 标准、并且有生图工具的智能体也能用：把文件夹复制到对应的 skills 目录。

## Use · 用法

Just describe the scene. You can attach a reference image for composition or style.

直接描述想要的画面即可，也可以附上一张参考图。

- `A narrow Paris street at blue hour, café terrace, climbing roses on the balconies`
- `画一张从高处看巴黎屋顶和埃菲尔铁塔的插画，金色午后`
- `A garden courtyard in Montmartre in soft morning light`

## Files · 文件

| Path | Contents |
|---|---|
| `SKILL.md` | Core rules and workflow · 核心规则与流程 |
| `references/monet-style.md` | Depth, detail, colour and brushwork guide · 景深、细节、色彩与笔触指南 |
| `references/prompts.md` | Prompt template · 提示词模板 |
| `references/examples.md` | Example scenes · 示例场景 |
| `references/paintings/` | Five Monet paintings used as optional style references · 五幅莫奈作品，可作为风格参考 |

## License · 许可

© 2026 Avelyn Zhou. Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/): free to use and adapt with attribution, **non-commercial use only**.

采用 CC BY-NC 4.0 许可：可以使用和修改，需署名，**仅限非商业用途**。

The Monet paintings in `references/paintings/` are in the public domain and are not covered by this license.

`references/paintings/` 中的莫奈作品属于公有领域，不受本许可约束。
