# 仿生工业设计展板 Skill

这是一个用于生成 A3 竖版仿生工业设计流程展板的 Skill。用户只需输入仿生对象，或输入“仿生对象＋产品类型”，Skill 就会直接调用图片生成能力，完成从生物观察到最终产品渲染的完整设计叙事。

## 主要能力

- 自动匹配适合的产品类型，也支持用户指定产品
- 固定 A3 竖版比例与专业工业设计作品集网格
- 完整呈现 7 个设计板块
- 保持草图、深化方案与最终渲染的产品造型一致
- 支持参考图、指定配色、材质和设计氛围
- 控制图中文字量，减少乱码

## 固定板块

1. BIOLOGICAL ORIGIN｜仿生原型
2. FEATURE EXTRACTION｜特征提取
3. FORM EVOLUTION｜形态演变
4. FORM EXPLORATION｜造型推演
5. DESIGN REFINEMENT｜设计深化
6. FINAL DESIGN｜最终设计
7. DESIGN HIGHLIGHTS｜设计亮点

## 安装

将以下目录复制到支持 Skills 的个人技能目录：

```text
skills/create-biomimetic-design-board-zh
```

该 Skill 需要环境中提供 `imagegen` 图片生成能力。

## 使用示例

仅输入仿生对象：

```text
使用 $create-biomimetic-design-board-zh，以水母为灵感生成A3仿生工业设计展板。
```

指定产品：

```text
使用 $create-biomimetic-design-board-zh，以蝴蝶为仿生对象，设计一款可折叠台灯。
```

附带风格要求：

```text
使用 $create-biomimetic-design-board-zh，以竹节为灵感设计一款落地灯，整体使用暖白、竹绿色和亚麻材质。
```

上传参考图时：

```text
使用 $create-biomimetic-design-board-zh，参考我上传图片的排版与配色，以莲蓬为灵感设计一款空气净化器。
```

## 输出说明

Skill 默认生成一张精修位图展板。A3 是构图与版式目标，并不等同于具有精确文字和可编辑图层的印刷源文件。如需 Illustrator、InDesign 或可编辑 PDF，应在生成概念图后单独制作生产文件。

## 版本

当前版本：v1.0.0。完整记录见 [CHANGELOG.md](CHANGELOG.md)。

## 许可证

本项目采用 MIT License。
