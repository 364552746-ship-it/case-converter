 # 🐱 喵喵大小写转换器 · Case Converter

  一个完全在浏览器本地运行的大小写 / 命名格式转换工具，粉嫩喵喵主题，粘贴文字一键变换。

  🔗 **在线使用**：https://364552746-ship-it.github.io/case-converter/

  ## ✨ 功能

  ### 大小写转换

  | 模式 | 示例 | 说明 |
  |------|------|------|
  | UPPERCASE | `HELLO WORLD` | 全部大写 |
  | lowercase | `hello world` | 全部小写 |
  | Title Case | `Hello World` | 单词首字母大写 |
  | Sentence case | `Hello world` | 句子首字母大写 |
  | tOGGLE cASE | `hELLO wORLD` | 大小写反转 |

  ### 命名格式

  | 模式 | 示例 |
  |------|------|
  | camelCase | `helloWorld` |
  | PascalCase | `HelloWorld` |
  | snake_case | `hello_world` |
  | kebab-case | `hello-world` |
  | CONSTANT_CASE | `HELLO_WORLD` |
  | dot.case | `hello.world` |
  | path/case | `hello/world` |
  | Train-Case | `Hello-World` |
  | COBOL-CASE | `HELLO-WORLD` |
  | Pascal_Snake | `Hello_World` |
  | SPACED CASE | `HELLO WORLD` |

  ### 全角 / 半角

  - 全角 → 半角：`ＡＢＣ１２３　ｘｙｚ` → `ABC123 xyz`
  - 半角 → 全角：`ABC123 xyz` → `ＡＢＣ１２３　ｘｙｚ`

  ### 其他

  - 📊 字数 / 字符实时统计
  - 📋 一键复制结果
  - 💾 下载为 `.txt`
  - 🔄 结果回填输入框（链式转换）
  - 🌙 深色模式（自动记住偏好）
  - ⌨️ 快捷键 `Ctrl + Enter` 触发最近一次转换

  ## 🚀 本地使用

  无需安装任何依赖，直接用浏览器打开 `index.html` 即可。

  ```bash
  # 或起一个本地服务器
  python -m http.server 4173
  # 然后访问 http://localhost:4173
  ```

  ## 🛠 技术特点

  - 纯单文件实现（HTML + CSS + JS 内联），零依赖、零构建
  - 所有转换完全在浏览器本地完成，**不上传任何数据**
  - 深色模式基于 CSS 变量（`:root` + `body.dark`），配色统一易维护

  ## 📦 部署到 GitHub Pages

  1. 在 GitHub 创建仓库 `case-converter`
  2. push 代码到 `master` 分支
  3. Settings → Pages → Source 选择 `master` 分支根目录
  4. 访问 `https://<用户名>.github.io/case-converter/`

  ## 📁 项目结构

  ```
  case-converter/
  ├── index.html    # 主应用（单文件，含全部 CSS / JS）
  ├── README.md     # 本说明
  ├── DEPLOY.md     # 部署指南
  └── .gitignore
  ```

  ## 📝 License

  仅供学习交流使用。

  需要调整（比如加徽章、改措辞、删某些段落）跟我说就行。
