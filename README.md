# 全景项目库原型

一个基于 Vue 3 和 Element Plus 的项目展示平台原型。

## 功能特点

- 项目库展示
- 深度资料查看
- 定制推广
- 视频播放
- 响应式设计

## 页面说明

- `project_library.html`: 项目库主页
- `project_list.html`: 项目列表页
- `deep_info.html`: 深度资料页
- `custom_promotion.html`: 定制推广页
- `ai_summary_dialog.html`: AI 总结对话框

## 技术栈

- Vue 3
- Element Plus
- HLS.js (视频播放)

## 开始使用

1. 克隆仓库：
```bash
git clone [repository-url]
```

2. 打开项目：
```bash
cd project_library_prototype
```

3. 使用本地服务器运行项目，例如：
```bash
python -m http.server 8000
# 或
php -S localhost:8000
# 或使用其他 HTTP 服务器
```

4. 在浏览器中访问：
```
http://localhost:8000/project_library.html
```

## 项目结构

```
project_library_prototype/
├── project_library.html    # 主页
├── project_list.html      # 项目列表
├── deep_info.html         # 深度资料
├── custom_promotion.html  # 定制推广
├── ai_summary_dialog.html # AI总结对话框
├── p5w_logo.png          # Logo图片
└── assets/               # 其他资源文件
```

## 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 注意事项

- 项目中的视频播放功能需要支持 HLS 的浏览器或 HLS.js 支持
- 部分功能需要现代浏览器支持
- 建议使用 Chrome 或 Firefox 最新版本访问

## 许可证

[添加许可证信息] 