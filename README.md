# 图片压缩网站

这是一个简单易用的在线图片压缩工具，采用苹果风格设计，具有清爽简约的界面。

## 在线演示

[点击访问在线演示](https://你的用户名.github.io/image-compressor)

## 功能特点

- 支持上传 PNG、JPG 格式图片
- 实时预览原图和压缩后的效果
- 显示压缩前后文件大小对比
- 可调节压缩比例
- 支持压缩后图片下载
- 响应式设计，支持各种设备访问

## 快速开始

1. 克隆项目
```bash
git clone https://github.com/你的用户名/image-compressor.git
```

2. 打开项目
```bash
cd image-compressor
```

3. 运行项目

由于项目使用纯静态文件，你可以直接用浏览器打开 index.html，或使用任何 Web 服务器托管项目。

例如使用 Python 快速启动一个本地服务器：
```bash
# Python 3
python -m http.server 8080

# 然后访问 http://localhost:8080
```

## 技术实现

- 使用纯 HTML5 + CSS3 + JavaScript 开发
- 采用 FileReader API 实现图片预览
- 使用 Canvas API 进行图片压缩
- 应用 Flexbox 布局实现响应式设计
- 采用苹果设计风格的 UI 组件

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 贡献指南

1. Fork 本项目
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 开源协议

本项目采用 MIT 协议开源，详见 [LICENSE](LICENSE) 文件。 