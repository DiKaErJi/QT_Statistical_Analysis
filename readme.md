# QT_Statistical_Analysis

## 概述

该项目是使用 C++ 和 Qt 框架开发的一个数据处理和可视化工具。它结合了第三方库 `xlsxdocument` 用于处理 Excel 文件，并使用 `QCustomPlot` 进行图表绘制。该工具能够实现对 Excel 文件和 txt 数据的读取、统计分析、数据表格显示、折线图和柱状图展示，并可以将图形以 PNG、JPG、PDF 等格式保存。

![image-20240523234950097](https://github.com/DiKaErJi/QT_Statistical_Analysis/blob/master/readme_images/image-20240523205356426.png)

## 功能介绍

### 数据读取
- **打开 Excel 文件**：通过界面上的按钮，可以选择并打开一个 Excel 文件，读取其中的数据。
- ![image-20240523205440859](https://github.com/DiKaErJi/QT_Statistical_Analysis/blob/master/readme_images/image-20240523205440859.png)
- **打开 txt 文件**：支持读取 txt 格式的数据文件，并将数据导入到程序中进行处理。
- ![image-20240523205500301](https://github.com/DiKaErJi/QT_Statistical_Analysis/blob/master/readme_images/image-20240523205500301.png)

### 数据处理
- **数据统计**：对导入的数据进行统计分析，包括计算平均值、最大值、最小值和总和等统计信息。
- **数据显示**：将读取和处理后的数据以表格形式显示在界面上。
- ![image-20240523235013484](https://github.com/DiKaErJi/QT_Statistical_Analysis/blob/master/readme_images/image-20240523205534869.png)

### 图表展示
- **折线图**：支持对数据生成折线图，以直观的方式展示数据的变化趋势。
- ![image-20240523235031965](https://github.com/DiKaErJi/QT_Statistical_Analysis/blob/master/readme_images/image-264565261.png)
- **柱状图**：支持对数据生成柱状图，方便进行数据比较分析。
- ![image-20240523235058398](https://github.com/DiKaErJi/QT_Statistical_Analysis/blob/master/readme_images/image-20240523205744397.png)

### 图形保存
- **保存为图片**：生成的图表可以保存为 PNG、JPG 等常见图片格式。
- **保存为 PDF**：支持将图表保存为 PDF 格式，方便打印和分享。

## 使用方法

### 环境配置
1. 安装 Qt 开发环境（建议使用 Qt 5.15 及以上版本）。
2. 安装 `QtXlsxWriter` 库，用于处理 Excel 文件。
3. 安装 `QCustomPlot` 库，用于图表绘制。

### 编译项目
1. 克隆或下载本项目源码。
2. 使用 Qt Creator 或命令行打开项目文件（.pro）。
3. 配置项目，确保所有依赖库正确链接。（主要修改mainwindows.cpp中qss中文件的位置，如1.png、blue1.qss等）
4. 编译并运行项目。

### 操作步骤
1. **打开数据文件**：启动程序后，点击界面上方的“打开 Excel”或“打开 txt”按钮，选择要导入的数据文件。
2. **数据统计**：导入数据后，点击“数据统计”按钮，程序会自动计算数据的平均值、最大值、最小值和总和，并在界面下方显示结果。
3. **图表展示**：
   - 点击“折线图”按钮，生成数据的折线图。
   - 点击“柱状图”按钮，生成数据的柱状图。
4. **保存图形**：生成图表后，可以点击“另存为图片”按钮，选择保存的格式和位置，将图表保存为 PNG、JPG 或 PDF 文件。

## 依赖库

- [Qt](https://www.qt.io/)：跨平台的C++图形用户界面应用程序框架。
- [QtXlsxWriter](https://github.com/dbzhang800/QtXlsxWriter)：用于在Qt应用程序中读写Excel文件的库。
- [QCustomPlot](http://www.qcustomplot.com/)：一个基于Qt的C++绘图控件，用于绘制2D图表。

## 结语

这个工具旨在为数据处理和可视化提供一个简便、快捷的解决方案，希望能为您的工作带来便利。同时，了解宇宙的终极奥秘也是人类永恒的追求。祝您使用愉快！
