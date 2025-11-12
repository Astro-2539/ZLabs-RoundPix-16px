![标题](/img/title.PNG "Title")

# Z Labs Round Bitmap 16px

「Z Labs Round Bitmap 16px」是一款规格为 16px 的像素字体（汉字实际占用大小为 15*15），采用圆体设计风格，西文字体按等宽规格设计。

本项目处于早期开发阶段，目前支持 GB/T 2312 一级汉字、常用西文及常用标点符号。

> [!WARNING]
> 
> 此字体仍处于早期开发阶段，除字符支持较少外，**尚未对汉字结构进行针对性调整**，
> 因此可能会出现汉字重心及字面大小不一致的情况。
> 
> 当前版本不代表最终版品质。
> 
> 如在使用过程中有任何问题，请及时在 Issues 中反馈。

> [!IMPORTANT]
> 
> 这是一个开源项目，字体部分采用 [OFL-1.1](https://openfontlicense.org/open-font-license-official-text/) 许可证授权，构建程序部分采用 MIT 许可证授权。您可以免费商用此字体。
> 

## 字体示例

![示例1](/img/Sample_1.PNG "Sample 1")

![示例2](/img/Sample_2.png "Sample 2")


## 字体覆盖范围

### 汉字

#### 中国大陆变体字形（CN）

&nbsp;&nbsp;&nbsp;&nbsp;🚧 GB/T 2312 （3847 / 6763）

&nbsp;&nbsp;&nbsp;&nbsp;🚧 《通用规范汉字表》（3800 / 8105）

&nbsp;&nbsp;&nbsp;&nbsp;🚧 Big5 常用汉字表（2512 / 5401）

&nbsp;&nbsp;&nbsp;&nbsp;🚧《常用国字标准字体表》（2460 / 4808）

&nbsp;&nbsp;&nbsp;&nbsp;🚧 GB/T 12345（2748 / 6866）

&nbsp;&nbsp;&nbsp;&nbsp;ℹ️ 共计支持汉字：3938

### 其他字符

本字体在 Unicode 私用区定义了部分字符，详情将于稍后上传。


## 从工程文件构建字体

本字体使用 [Bits'n'Picas](https://github.com/kreativekorp/bitsnpicas) 制作。运行 `./tools/build.py` 即可生成字体。

构建流程依赖 `fonttools` 库、`pixel_font_builder` 库和 `kbitfont` 库。

构建流程详见 `Tools` 文件夹下的自述文件。
    

## 字体授权

本项目授权分为「字体」及「构建代码」两部分。

### 字体

使用 [SIL Open Font License 1.1](https://openfontlicense.org/open-font-license-official-text/) 许可证授权。

您可以将此字体用于包含商用与嵌入式使用在内的多种用途，而无须取得字体作者的额外授权。

再分发此字体时，您应当注明 OFL 授权协议的原文或链接。

根据 OFL 协议，如使用此字体制作衍生字体，那么衍生字体也必须同样遵循 OFL 协议。您不得单独售卖此字体。

作者保留字体名称「Z工坊 / Z Labs」。

### 构建代码

使用 MIT 许可证授权。


## 鸣谢

[Bits'N'Picas](https://github.com/kreativekorp/bitsnpicas) 提供像素字形编辑软件。

[@狼人小林](https://github.com/TakWolf) 提供技术支持。

## 相关资料

[字统网](https://zi.tools/) - 漢字源、形、音、義、碼网羅站點
