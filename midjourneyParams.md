# 参数设置

## Aspect Ratios 横纵比
--aspect, or --ar Change the aspect ratio of a generation.The default aspect ratio is 1:1.--aspect must use whole numbers. Use 139:100 instead of 1.39:1.

```bash
--ar 4:5
--ar 2:3
```

### 常见的缩放比
--aspect 1:1 Default aspect ratio.
--aspect 5:4 Common frame and print ratio.
--aspect 3:2 Common in print photography.
--aspect 7:4 Close to HD TV screens and smartphone screens.

## Chaos
The --chaos or --c parameter influences how varied the initial image grids are. High --chaos values will produce more unusual and unexpected results and compositions. Lower --chaos values have more reliable, repeatable results.

```bash
imagine/ prompt watermelon owl hybrid --c 100
```

## Quality GPU生成图片的耗时
The --quality or --q parameter changes how much time is spent generating an image. Higher-quality settings take longer to process and produce more details. Higher values also mean more GPU minutes are used per job. The quality setting does not impact resolution.
--quality <.25, .5, 1, or 2>, or --q <.25, .5, 1, or 2> How much rendering quality time you want to spend. The default value is 1. Higher values cost more and lower values cost less.

```bash
--q 2
```

