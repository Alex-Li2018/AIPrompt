# midjourney promapt

## Medium
## painting 油画
- Cute cartoon style painting 可爱卡通油画
### illustration 插画
- national trendy illustration 国朝插画
- Children's book illustration 儿童插画
- Matisse-inspired illustration 受Matisse启发的插图
- paper illustration 纸插画
- Chinese illustration on white background 白底中国插画
- Chinese ancient style 中国古代风格

## Lighting 灯光
- natural lighting 自然采光

## style 风格
- minimalism 极简
- romantic 浪漫
- 3d relief 3d浮雕
- line art 线条艺术
- comics style 漫画风格
- clean logo 简洁的logo
- muted colors 柔和色彩
- watercolor 水彩画
- Chinese fairy tale 中国童话

## color 颜色
- dark
- pastel color 柔和的颜色
- warm color background 暖色背景
- 3d rendering 3D渲染

## 导演名/人名
- [hr giger 瑞士超现实主义画家](https://zh.wikipedia.org/zh-cn/H%C2%B7R%C2%B7%E5%90%89%E6%A0%BC%E5%B0%94)
- [亨利·马蒂斯 法国油画家](https://zh.wikipedia.org/wiki/%E4%BA%A8%E5%88%A9%C2%B7%E9%A9%AC%E8%92%82%E6%96%AF)
- picasso 毕加索
- Pixar style 皮克斯风格
- Disney style 迪士尼风格

## content
- endless outer space sci-fi landscap 无尽的外天空科幻风景
- Night, starry sky, Milky Way 夜星空银河 
- the painting creates a deep emotional atmosphere and unique cultural charm for the viewers 通过运用柔和的色彩和细腻的笔触,为观者营造出深沉的情感氛围和独特的文化魅力 
- The light ink colors in contrast with soft and light brushstrokes, create a strong sense of light and dark contrast 淡淡的墨色与柔和轻盈的笔触形成强烈的明暗对比 
- luminous xxx 发光的
- Full-body portraits in 3D 全身像
- shot straight ahead 目光向前

## 动作延续
- panels with different poses 不同的pose

## other
- rich details 细节丰富
- super wide angle 超广角
- advanced sense of color scheme 高级配色
- colour palette 调色盘
- no text 无文本
- Multi-dimensional paper kirigami craft 多维剪纸工艺
- wallpaper 墙纸 壁纸
- personification 拟人
- imperious 霸道
- spectacular 震撼
- HD 4K 高清 4K
- 35mm shot 35毫米镜头
- dramatic 戏剧性
- stunning 逼真
- panorama 全景
- movie light 电影灯光
- detailed textures and lighting 详细的纹理与照明
- Blizzard Entertainment 暴雪娱乐
- national tide wind 国风
- movie quality 电影画质
- lumen render 流明渲染
- 3d relief 3d 浮雕
- full body shoot 全身照
- deconstruction 解构
- character design 人物设计
- knight-errant 武侠
- Chinese landscape painting 中国山水画
- ink wash style 水墨画

## 语法格式

```js
[pre-prompt]::[BASE PROMPT]:1.5 --seed [SEED ID] --stylize [stylize value]
```
```bash
/imagine playful smile::Prince Rodrick the Great, elderly medieval prince, character design, in style of Rembrandt::1.5 — seed 3299135161 — stylize 800
```
你可以改变基础提示的权重以及stylize的值来微调图像

```bash
/imagine <facial expression>::<weight>::<base prompt>::<weight> — seed ID
```

In order to place a character in a different setting, one would use an image prompt or prompts, along with prompt of the character in the setting:

```bash
- /imagine <image URL> <character in a setting>::<weight>::<base prompt>::<weight> — seed ID
```

In order to place a character taking an action, one would use an image prompt or prompts, along with prompt of the character taking an action:

```bash
/imagine <image URL> <character taking an action>::<weight>::<base prompt>::<weight> — seed ID
```

It is challenging to get images of a consistent character in Midjourney, but there are definitely ways to “hack” it in order to maintain some consistency.