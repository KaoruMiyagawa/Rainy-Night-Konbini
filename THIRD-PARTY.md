# 第三方代码与资源声明

## Three.js

- **组件：** Three.js，版本 r180（页面内嵌构建信息 `revision: "180"`）。
- **用途：** WebGL 渲染、相机、几何体、材质、灯光和动画。
- **来源：** Three.js 官方项目代码以打包形式保存在 `index.html` 中；页面末尾保留了 Bundled license information。
- **许可证：** MIT。内嵌声明标注 `Copyright 2010-2025 Three.js Authors`，并包含 `SPDX-License-Identifier: MIT`。
- **OrbitControls：** 页面内嵌相机控制器代码，提供旋转、缩放和平移功能；随 Three.js 项目代码按 MIT 许可证声明。

Three.js MIT 许可证文本：

```text
MIT License

Copyright 2010-2025 Three.js Authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 项目图片与其他资源

- `preview.png` 与 `bar-close.png` 是随现有项目提供的街区全景和酒吧近景截图。
- `docs/screenshots/scene.png` 是本次使用 Microsoft Edge 本地打开场景后生成的验证截图。
- 在 HTML 中未发现独立 GLTF/FBX 模型或由 `TextureLoader` 加载的外部贴图；场景以 HTML 内嵌代码呈现。
- 原始分享包 `雨夜便利店-分享包.zip` 中的 HTML 和两张 PNG 与工作目录对应文件逐字节一致。该 ZIP 是交付副本，不纳入 Git。
- 现有图片没有单独的来源或授权元数据；它们表现为本项目场景截图，而非第三方模型或贴图。公开发布前仍应由项目维护者确认其拥有截图的再分发权。

## 本项目许可证

仓库当前没有为项目自身代码声明整体许可证。Three.js 的 MIT 声明只覆盖对应第三方代码，不等同于项目作者为整个场景授予 MIT 许可；如需允许他人复用项目内容，应另行选择并添加项目许可证。
