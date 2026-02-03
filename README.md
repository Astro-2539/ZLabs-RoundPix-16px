**简体中文** | [English](/README_EN.md)

# Z Labs RoundPix 16px

![Title](/img/幻灯片1.PNG "Title")

> [!WARNING]
> 
> 本字体家族的英文名称已由"Z Labs Round Bitmap 16px"变更为"Z Labs RoundPix 16px"（详见[Issues #1](https://github.com/Astro-2539/ZLabs-Round-Bitmap-16px/issues/1)），中文名称不变。
> 
> 同时，**字体文件中的字体名称**也已经同步变更。由于名称不同，新旧版本字体可以共存，**您需要在您的项目中手动切换至更名后的新版字体**。
> 
> 如有疑问或建议，请在 Issue #1 中回复。

**「Z Labs RoundPix 16px」（Z工坊像素圆体 16px）** 是一款规格为 16px 的中文像素字体（汉字实际占用大小为 15*15），采用圆体字形风格，西文字符按等宽规格绘制。

本项目处于开发阶段，目前支持 GB/T 2312 一级汉字及部分二级汉字、常用西文及常用标点符号，可满足较为简单的简体中文汉字使用需求。

> [!WARNING]
> 
> 此字体仍处于积极开发阶段，字形细节将不断调整及完善。
> 
> 如在使用过程中有任何问题，请及时在 Issues 中反馈。

> [!IMPORTANT]
> 
> 我们正在就像素字体的使用需求情况进行调查。
>
> 如果可以，请帮忙填写下方的问卷，非常感谢！
>
> https://f.kdocs.cn/g/EwkAraFp/
> 

## 字体介绍

![介绍页](/img/幻灯片2.PNG "介绍页")

![示例页](/img/幻灯片3.PNG "示例页")

![像素点样式](/img/幻灯片4.PNG "像素点样式")

![授权页](/img/幻灯片5.PNG "授权页")

[点击查看字体故事](/docs/FontStory_1.md)

## 字形变体

目前仅支持中国大陆（CN）字形变体。

*注：日本（JP）字形变体已经开始制作，仓库已更新相关文件。*

*取形参考自「Zen Maru Gothic」，大致以JIS90为基准，而非采用较新的JIS2004标准。*

*由于现阶段支持字符较少，未在Release中释出，如有需要可自行从源文件编译。*

## 字体覆盖范围

### 汉字

#### 中国大陆变体字形（CN）

&nbsp;&nbsp;&nbsp;&nbsp;🚧 GB/T 2312 （5996 / 6763）

&nbsp;&nbsp;&nbsp;&nbsp;🚧 《通用规范汉字表》（5900 / 8105）

&nbsp;&nbsp;&nbsp;&nbsp;🚧 Big5 常用汉字表（3233 / 5401）

&nbsp;&nbsp;&nbsp;&nbsp;🚧《常用国字标准字体表》（3018 / 4808）

&nbsp;&nbsp;&nbsp;&nbsp;🚧 jf7000 当务字集基本包（3643 / 6373）

&nbsp;&nbsp;&nbsp;&nbsp;🚧 GB/T 12345（4255 / 6866）

&nbsp;&nbsp;&nbsp;&nbsp;🚧 JIS X 0208（3234 / 6355）

&nbsp;&nbsp;&nbsp;&nbsp;ℹ️ 共计支持汉字：6216



## 从工程文件构建字体

本字体使用 [Bits'n'Picas](https://github.com/kreativekorp/bitsnpicas) 制作。运行 `./tools/build.py` 即可生成字体。

构建流程依赖 `fonttools` 库、`pixel_font_builder` 库和 `kbitfont` 库。

## 字体授权

本项目授权分为「字体」及「构建代码」两部分。

### 字体

使用 [SIL Open Font License 1.1](https://openfontlicense.org/open-font-license-official-text/) 许可证授权。

您可以将此字体用于包含商用与嵌入式使用在内的多种用途，而无须取得字体作者的额外授权。

再分发此字体时，您应当注明 OFL 授权协议的原文或链接。

根据 OFL 协议，如使用此字体制作衍生字体，那么衍生字体也必须同样遵循 OFL 协议（或与之兼容的协议）。您不得单独售卖此字体软件。

作者保留字体名称「Z工坊 / Z Labs」。

### 构建代码

使用 MIT 许可证授权。


## 鸣谢

[Bits'N'Picas](https://github.com/kreativekorp/bitsnpicas) 提供像素字形编辑软件。

[@狼人小林](https://github.com/TakWolf) 提供技术支持。

## 相关资料

[字统网](https://zi.tools/) - 漢字源、形、音、義、碼网羅站點

## 项目 Stars 统计图

[![Stargazers over time](https://starchart.cc/Astro-2539/ZLabs-RoundPix-16px.svg?variant=adaptive)](https://starchart.cc/Astro-2539/ZLabs-RoundPix-16px)
