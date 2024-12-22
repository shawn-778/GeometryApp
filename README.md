# GeometryApp
A PyQt5 tool for geometric shape operations and intersection detection
几何图形相交检测工具

## 项目简介

GeometryApp 是一个基于 PyQt5 的用户界面工具，支持绘制线段、三角形和矩形，并能够检测任意两个图形之间的相交情况及交点坐标。

## 功能

1. **图形绘制**
   - **线段**：通过点击两点绘制。
   - **三角形**：通过点击三个点绘制。
   - **矩形**：通过点击并拖动确定对角线两个端点绘制。

2. **相交检测**
   - 检测任意两个图形是否相交。
   - 显示相交点的坐标，并在界面上高亮显示交点。

3. **用户操作**
   - 绘图工具选择（线段、三角形、矩形）。
   - 检测相交按钮。
   - 清除画布按钮。
   - 显示相交结果和交点坐标。

## 安装与运行

### 1. 克隆仓库

```bash
git clone https://github.com/您的用户名/GeometryApp.git
cd GeometryApp
