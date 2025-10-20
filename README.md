# MathBox Mathematical Interaction

这是一个基于 **MathBox + Three.js** 的数学交互示例项目，目的是展示动态数学可视化和用户拖拽交互效果。

## 📂 Demos

- [Trigonometric Functions and Inverse Trigonometric Functions - Parameter Correspondence](https://brevis14.github.io/MathBox-Mathematical-Interaction/TF_ITF.html)
- [Sin Function - with Control Slider](https://brevis14.github.io/MathBox-Mathematical-Interaction/SinF-ControlSlider.html)
- [3D Euler's Formula Projection Demonstration](https://brevis14.github.io/MathBox-Mathematical-Interaction/3dEulersProjection.html)
- [From the Unit Circle to Trigonometric Functions](https://brevis14.github.io/MathBox-Mathematical-Interaction/UnitCircle2TF.html)
- [Plane Section of a Cube - Highlighted Cross-Section](https://brevis14.github.io/MathBox-Mathematical-Interaction/PlaneSection-Cube.html)
- [Plane Section of a Cube - More Interactions](https://brevis14.github.io/MathBox-Mathematical-Interaction/PSlight_dark-cube.html)

👉 如果直接访问 [主入口](https://brevis14.github.io/MathBox-Mathematical-Interaction/)，会看到一个导航页，里面也有以上所有链接。

## ⚙️ 技术栈

- HTML5 + CSS3 + JavaScript
- [MathBox.js](http://mathbox.io)  
- WebGL（通过 MathBox 封装）

## 🚀 本地运行

```bash
# 克隆仓库
git clone https://github.com/Brevis14/MathBox-Mathematical-Interaction.git

# 进入目录
cd MathBox-Mathematical-Interaction

# 用浏览器直接打开 demo1.html / demo2.html / demo3.html
# 或者用 VSCode Live Server / python -m http.server 启动本地服务器
```

## 🔧 功能

- **交互功能**：  
  - 用户可以拖动数学图像中的控制点，动态改变函数图像或几何图形（如平面截面）。  
  - 截面联动更新、交点计算、平面法向变化等视觉反馈及时响应。  
