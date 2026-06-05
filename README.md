# 傅里叶级数与傅里叶变换：从声音到频谱

A Chinese-language interactive teaching page that explains Fourier series and Fourier transforms through animated visualizations — decomposing complex waveforms into simple sine waves.

在线演示：[fourier-explained](https://icyjerry.github.io/fourier-explained/)

## 内容涵盖

- 🎵 **谐波叠加动画** — 可调 1-25 个频率，观察方波如何由正弦波叠加而成
- 🔄 **时域 vs 频域** — 同一信号的双重视角对比
- 📐 **傅里叶级数** — 周期函数的分解：找周期 → 整数倍频率 → 算权重
- 📈 **从级数到变换** — T→∞ 时离散频谱变为连续频谱的动画演示
- 🎛️ 多个交互式滑块实时控制参数

## 技术栈

纯前端，单文件 HTML（~2400 行），零依赖：
- Canvas API 绘制波形动画
- CSS 自定义属性 + 柔和设计语言
- 响应式布局，桌面/移动端均可浏览

## 本地运行

直接用浏览器打开 `index.html` 即可，无需构建。

```bash
open index.html
```

## License

MIT
