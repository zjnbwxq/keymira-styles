# keymira-styles

欢迎来到 Keymira 样式分享页面！这里列出了所有可用的自定义样式。要使用这些样式，只需点击样式名称旁边的链接，然后将链接复制到 Keymira 的"下载样式"对话框中。

## 可用样式

1. [极简风格](https://raw.githubusercontent.com/yourusername/keymira-styles/main/minimal)
   - 简洁的黑白图标设计

2. [霓虹风格](https://raw.githubusercontent.com/yourusername/keymira-styles/main/neon)
   - 明亮的霓虹色彩图标

3. [复古风格](https://raw.githubusercontent.com/yourusername/keymira-styles/main/retro)
   - 怀旧的像素艺术图标

## 如何贡献

如果您创建了自己的样式并想与他人分享，请按照以下步骤提交拉取请求：

1. Fork 这个仓库
2. 创建一个新的文件夹，以您的样式名称命名
3. 在文件夹中添加 `style.json` 文件和所有必要的SVG文件
4. 更新 README.md，添加您的样式信息
5. 提交拉取请求

## 如何创建本地样式

如果您想创建一个本地样式并导入到Keymira中，请按照以下步骤操作：

1. 创建一个新文件夹，以您的样式名称命名。
2. 在该文件夹中创建一个 `style.json` 文件，包含以下内容：
   ```json
   {
     "name": "您的样式名称",
     "description": "样式描述",
     "floating_window": {
       "background_color": "#000000",
       "background_opacity": 0.8,
       "border_color": "#FFFFFF",
       "border_width": 2,
       "border_radius": 10,
       "width": 300,
       "height": 100
     },
     "text": {
       "font_family": "Arial",
       "font_size": 16,
       "font_color": "#FFFFFF",
       "font_weight": "bold"
     },
     "icons": {
       "ctrl": "ctrl.svg",
       "shift": "shift.svg",
       "alt": "alt.svg"
     }
   }
   ```
3. 将所有引用的SVG文件放在同一文件夹中。
4. 在Keymira应用中，点击"导入本地样式"按钮，然后选择您创建的样式文件夹。

注意：确保 `style.json` 中的 "name" 字段与文件夹名称相匹配，并且所有引用的SVG文件都存在于文件夹中。

感谢您的贡献！
