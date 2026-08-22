# LaTeX 简体中文元素周期表

一张用 LaTeX 精心排版的简体中文元素周期表：信息完整、版式干净、打印友好。

## 预览

![预览](ctex-ptable.png)

## 特性

- 原子序数
- 元素符号
- 原子量
- 中文名与拼音
- 英文名
- 简化电子排布式

## 数据来源

1. 原子量与元素名称：以国际纯粹与应用化学联合会（IUPAC）的最新数据为准。稳定元素及部分长寿命放射性元素的原子量一般保留四位有效数字。唯一的例外是锂，其采用了 IUPAC 推荐的三位有效数字精度。
   - [Periodic Table of Elements - IUPAC | International Union of Pure and Applied Chemistry](https://iupac.org/what-we-do/periodic-table-of-elements/)

2. 电子排布：区分了实验确认与理论预测的数据来源。
   - 元素 1-108：依据美国国家标准与技术研究院（NIST）原子光谱数据库的实验数据。
     - [NIST: Atomic Spectra Database - Ionization Energies Form](https://physics.nist.gov/PhysRefData/ASD/ionEnergy.html)
   - 元素 109-118：采用当前主流的理论预测值，整理与校对参考了维基百科的数据页。
     - [Electron configurations of the elements (data page) - Wikipedia](https://en.wikipedia.org/wiki/Electron_configurations_of_the_elements_(data_page))

## 免责声明

我尽可能核对并更新数据，但难免有疏漏或滞后。请仅将本项目用于学习与参考，不建议在对精度有严格要求的科研或生产环境中直接使用。  
如果发现数据或排版问题，欢迎通过 Issue 或 Pull Request 指正，感谢你的帮助。

## 致谢

感谢 [文渊字体](https://github.com/takushun-wu/WenYuanFonts) 的开发者 takushun-wu，字体覆盖了所有元素的中文名。编译前请先安装该字体。

本项目受到 [PaNDanese/periodic-table](https://github.com/PaNDanese/periodic-table) 的启发，并在早期基于其代码开发。感谢原作者 [Ivan Griffin](https://github.com/griffini) 和 [Paul Danese](https://github.com/PaNDanese) 的出色工作。

## 许可证

本项目采用 LaTeX Project Public License v1.3c 许可证。
