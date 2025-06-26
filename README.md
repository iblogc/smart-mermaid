# Smart Mermaid: AI 驱动的文本转 Mermaid 图表工具

Smart Mermaid 是一款利用人工智能技术，将您的文本描述智能转换为 Mermaid 格式图表代码，并实时渲染成可视化图表的 Web 应用。无论是流程图、序列图、甘特图还是状态图，只需输入文本，AI 即可为您生成相应的图表。

## 访问体验

[https://smart-mermaid.aizhi.site](https://smart-mermaid.aizhi.site)

**提示：** 本应用完全免费，应用已内置 API Key，您可以直接免费使用。为防止资源滥用，我们设置了每位用户每日 5 次的免费生成额度。
如有更多需求，可联系作者免费添加（为避免骚扰，加好友时请注明目的）。

<img src="https://github.com/user-attachments/assets/c41a6245-f169-4ede-afad-c2e9f5955343" width="200px">


## 效果预览

![PixPin_2025-05-23_11-25-46](https://github.com/user-attachments/assets/7ad74f73-68f3-499f-bcb4-f2b3e67336e8)

*图：Smart Mermaid 操作界面与生成的图表*

## 核心优势

* **简化图表绘制**：告别手动编写 Mermaid 代码的繁琐，通过自然语言描述即可快速生成图表。
* **提升效率**：将想法迅速转化为可视化图表，节省您在文档撰写和沟通演示上的时间。
* **智能辅助**：AI 自动分析文本，理解意图，并选择合适的图表类型（或由您指定）。
* **灵活配置**：支持自定义 AI 服务配置，满足不同用户的需求。
* **专业体验**：提供专业级的图表编辑和查看体验，支持多种渲染模式。

## 主要功能

### 🎯 核心功能

* **灵活的文本输入**:
    * 直接在编辑器中手动输入或粘贴文本。
    * 支持上传文件（.txt, .md, .docx 格式）。
    * 最大支持 20,000 字符的输入长度。

* **智能 AI 转换**:
    * 集成先进 AI 模型分析文本内容。
    * 支持多种AI模型选择（DeepSeek V3、DeepSeek R1等）。
    * 支持自动识别最佳图表类型或由用户指定。
    * 精准生成符合 Mermaid 规范的图表代码。
    * 实时流式生成，展示AI思考过程。

* **双重渲染模式**:
    * **Excalidraw渲染器**：手绘风格的可编辑图表，支持元素拖拽和样式修改。
    * **Mermaid渲染器**：精确的标准图表，支持专业级缩放和视图控制。
    * 一键切换渲染模式，满足不同的使用场景。

* **专业级代码编辑器**:
    * 集成 CodeMirror 编辑器，支持 Mermaid 语法高亮。
    * 可调节编辑器高度（小、中、大、特大）。
    * 实时代码验证和预览更新。

### 🔧 高级功能

* **智能界面设计**:
    * **左侧面板折叠**：一键隐藏编辑面板，获得更大的图表预览空间。
    * **响应式布局**：完美适配桌面端和移动端设备。
    * **暗色模式支持**：提供舒适的夜间使用体验。

* **AI 智能自动改错功能** ⭐ **新功能**:
    * **AI智能分析**：使用先进AI模型深度分析Mermaid代码问题。
    * **专业修复**：不仅修复语法错误，还提供代码优化建议。
    * **上下文理解**：AI理解图表结构，提供针对性修复方案。
    * **一键修复**：在编辑器和主界面都提供AI修复按钮。
    * **安全回退**：AI失败时自动使用基础规则修复。
    * **详细反馈**：提供修复说明和改进建议。

* **一键方向切换功能** ⭐ **新功能**:
    * **横纵切换**：一键在横向(LR)和纵向(TD)布局间切换。
    * **智能识别**：自动检测当前图表方向并进行相应转换。
    * **快捷操作**：在编辑器和主界面都提供方向切换按钮。
    * **布局优化**：根据内容特点选择最佳显示方向。

* **增强的视图控制**:
    * **缩放功能**：Shift + 滚轮缩放，避免浏览器冲突。
    * **平移操作**：鼠标拖拽移动视图，键盘快捷键支持。
    * **视图重置**：一键恢复默认视图状态。
    * **全屏模式**：最大化工作空间，专注图表编辑。

* **强大的导出功能**:
    * **SVG导出**：高质量矢量图下载。
    * **PNG导出**：适用于文档和演示的位图格式。
    * **代码复制**：一键复制 Mermaid 代码到剪贴板。

* **自定义 AI 配置**:
    * 支持配置您自己的 AI 服务 API（OpenAI、Azure OpenAI、其他兼容服务）
    * 可自定义 API URL、API Key 和模型名称
    * 支持模型切换，选择最适合的AI模型
    * 配置自己的 AI 服务后享有无限使用权限

* **访问权限管理**:
    * 内置访问密码功能，验证通过后可享有无限使用权限
    * 支持多种使用模式：免费限量 → 密码验证 → 自定义配置

* **使用量统计**:
    * 实时显示剩余使用次数
    * 本地存储使用记录，按日重置

## 使用权限说明

Smart Mermaid 提供三种使用模式：

### 📊 免费模式
- **限制**: 每日 5 次免费生成
- **适用**: 轻量级用户，偶尔使用
- **无需配置**: 开箱即用

### 🔑 密码模式  
- **权限**: 输入访问密码后享有无限使用
- **适用**: 经授权的用户
- **获取方式**: 联系作者获取访问密码

### ⚙️ 自定义配置模式
- **权限**: 无限制使用
- **适用**: 有自己 AI 服务的用户  
- **配置**: 在设置中填入您的 API 配置
- **优势**: 完全自主控制，无依赖

## 使用方法

### 基础使用流程

1.  **输入描述文本**:
    * 在左侧的文本区域直接输入或粘贴您的图表描述。
    * 或者点击上传按钮，选择本地的 `.txt`, `.md`, 或 `.docx` 文件。

2.  **选择配置选项**:
    * 从下拉菜单中选择您期望生成的图表类型（如流程图、序列图等）。
    * 选择AI模型（如有无限权限，可在模型选择器中切换）。
    * 您也可以选择"自动选择"，让 AI 根据文本内容判断最合适的图表类型。

3.  **生成图表**:
    * 点击"生成图表"按钮。
    * AI 将开始处理您的文本，实时显示生成过程。
    * 生成的 Mermaid 代码和渲染图表将在右侧区域显示。

4.  **查看与编辑**:
    * 在代码编辑器中查看或修改 Mermaid 代码，图表会实时更新。
    * 使用视图控制按钮进行缩放、平移、重置等操作。
    * 切换渲染模式体验不同的图表风格。

5.  **导出和分享**:
    * 使用导出功能下载 SVG 或 PNG 格式图表。
    * 复制 Mermaid 代码用于其他平台。

### 界面操作指南

#### 左侧编辑面板
- **文本输入区域**: 支持手动输入或文件上传
- **代码编辑器**: 实时编辑和预览 Mermaid 代码
- **高度调节**: 四档预设高度（小、中、大、特大）
- **面板折叠**: 点击隐藏按钮获得更大预览空间

#### 右侧预览面板
- **渲染模式切换**: 在 Excalidraw 和 Mermaid 之间切换
- **视图控制**: 缩放、平移、重置、全屏等操作
- **导出功能**: 下载图表或复制代码

#### 交互快捷键
- **Shift + 滚轮**: 图表缩放
- **Ctrl + +/-/0**: 缩放控制和重置
- **鼠标拖拽**: 平移视图
- **双指触控**: 移动端缩放支持

### 解锁无限使用

#### 方法一：使用访问密码
1. 点击右上角的设置按钮
2. 在"访问密码"选项卡中输入密码
3. 验证成功后即可享有无限使用权限

#### 方法二：配置自定义 AI 服务
1. 点击右上角的设置按钮
2. 在"AI 配置"选项卡中填入您的配置：
   - **API URL**: 您的 AI 服务地址（如：`https://api.openai.com/v1`）
   - **API Key**: 您的 API 密钥
   - **模型名称**: 使用的模型（如：`gpt-3.5-turbo`, `gpt-4`等）
3. 保存配置后即可无限使用，并可在模型选择器中切换不同模型

#### 获取访问权限
- **联系作者**: 扫描应用内二维码或通过 GitHub Issues 联系
- **自备 AI 服务**: 使用您自己的 OpenAI API Key 或其他兼容服务

## 技术选型

* **前端框架**: Next.js 15 (采用 App Router)
* **UI 组件库**: shadcn/ui + Radix UI
* **CSS 框架**: Tailwind CSS v4
* **代码编辑器**: CodeMirror 6 (支持 Mermaid 语法高亮)
* **图表渲染与处理**:
    * Excalidraw (`@excalidraw/excalidraw`)
    * Mermaid (`mermaid`)
    * Mermaid 到 Excalidraw 转换 (`@excalidraw/mermaid-to-excalidraw`)
* **文件解析**: mammoth (用于处理 `.docx` 文件)
* **AI 服务**: 兼容 OpenAI API 模式
* **状态管理**: React Hook + Local Storage
* **主题支持**: next-themes (暗色/亮色模式)

## 部署指南

### 🐳 Docker 一键部署 ⭐ **新功能**

最简单的部署方式，无需配置 Node.js 环境：

```bash
# 克隆项目
git clone https://github.com/yourusername/smart-mermaid.git
cd smart-mermaid

# 一键启动
docker-compose up -d

# 访问应用
# 打开浏览器访问：http://localhost:3000
```

详细的 Docker 部署说明请参考：[Docker 部署指南](./DOCKER_DEPLOY.md)

### 🐋 Docker 手动构建部署

您也可以选择手动构建和运行 Docker 镜像：

```bash
# 构建 Docker 镜像
docker build -t smart-mermaid .

# 运行 Docker 容器
docker run -d \
  --name smart-mermaid \
  -p 8004:3000 \
  --restart always \
  -e AI_API_URL=https://api.openai.com/v1 \
  -e AI_API_KEY=sk-xxxxxxxxxxxxxxxx \
  -e ACCESS_PASSWORD=your_password \
  smart-mermaid
```

**Docker 环境变量说明**:

您可以通过环境变量来配置应用，与 `.env.local` 文件中的配置项相同：

| 环境变量 | 说明 | 示例值 |
|---------|------|-------|
| `AI_API_URL` | AI 服务 API 的基础地址 | `https://api.openai.com/v1` |
| `AI_API_KEY` | AI 服务 API 密钥 | `sk-xxxxxxxxxxxxxxxx` |
| `AI_MODEL_NAME` | 使用的 AI 模型名称 | `gpt-3.5-turbo` |
| `AI_MODELS` | 可选模型列表，格式为"模型ID:显示名称:描述"，使用半角逗号连接多个模型 | `gpt-3.5-turbo:GPT-3.5:快速响应,gpt-4:GPT-4:高级推理` |
| `NEXT_PUBLIC_MAX_CHARS` | 最大输入字符数 | `20000` |
| `NEXT_PUBLIC_DAILY_USAGE_LIMIT` | 每日免费使用次数 | `5` |
| `ACCESS_PASSWORD` | 访问密码 | `your_password` |

这些环境变量可以在 Docker 运行命令中使用 `-e` 参数指定，也可以使用 Docker Compose 配置文件进行设置。

### 📦 本地部署指南

#### 环境要求

* Node.js 18.x 或更高版本
* npm 或 yarn 包管理工具

#### 安装步骤

1.  **克隆代码仓库**:
    ```bash
    git clone https://github.com/yourusername/smart-mermaid.git
    cd smart-mermaid
    ```
    *(请将 `yourusername` 替换为实际的仓库路径)*

2.  **安装项目依赖**:
    ```bash
    npm install
    # 或者
    yarn install
    ```

3.  **配置环境变量**:
    在项目根目录下创建 `.env.local` 文件，并填入以下配置：
    ```plaintext
    # AI 服务配置（必需）
    AI_API_URL=https://api.openai.com/v1
    AI_API_KEY=在此处填入您的API密钥
    AI_MODEL_NAME=gpt-3.5-turbo
    
    # 应用配置
    NEXT_PUBLIC_MAX_CHARS=20000
    NEXT_PUBLIC_DAILY_USAGE_LIMIT=5
    
    # 访问密码（可选）
    ACCESS_PASSWORD=设置您的访问密码
    ```

    **环境变量说明**:
    * `AI_API_URL`: AI 服务 API 的基础地址（不包含 `/chat/completions`）
    * `AI_API_KEY`: 您的 AI 服务 API 密钥
    * `AI_MODEL_NAME`: 指定使用的 AI 模型名称
    * `NEXT_PUBLIC_MAX_CHARS`: 允许用户输入的最大字符数（默认 20,000）
    * `NEXT_PUBLIC_DAILY_USAGE_LIMIT`: 每用户每日免费使用次数限制（默认 5）
    * `ACCESS_PASSWORD`: 可选，设置后用户可通过输入此密码获得无限使用权限

4.  **启动开发服务器**:
    ```bash
    npm run dev
    # 或者
    yarn dev
    ```

5.  **访问应用**:
    在浏览器中打开 `http://localhost:3000` 即可访问本地部署的应用。

### 生产环境部署

```bash
# 构建生产版本
npm run build

# 启动生产服务器
npm run start
```

## 项目特色

### 🎨 用户体验优化
- **流畅动画**: 平滑的面板折叠和视图切换动画
- **响应式设计**: 完美适配各种屏幕尺寸
- **直观操作**: 清晰的图标和操作提示
- **无障碍支持**: 良好的键盘导航和屏幕阅读器支持

### 🚀 性能优化
- **动态加载**: Excalidraw 组件动态导入，减少初始加载时间
- **防抖处理**: 避免频繁重渲染，提升交互流畅度
- **智能缓存**: 本地存储用户配置和偏好设置
- **内存管理**: 及时清理事件监听器，防止内存泄漏

### 🔧 技术亮点
- **模块化设计**: 组件化架构，易于维护和扩展
- **类型安全**: 完整的参数验证和错误处理
- **事件系统**: 跨组件的全局事件通信机制
- **配置中心**: 统一的配置管理服务

## 欢迎贡献与反馈

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=liujuntao123/smart-mermaid&type=Date)](https://www.star-history.com/#liujuntao123/smart-mermaid&Date)

如果您在使用过程中遇到任何问题，或有功能建议，欢迎通过 GitHub Issues 提出。也欢迎您 Fork本项目并提交 Pull Requests 参与贡献！

如果这个项目对您有帮助，请给我们一个 ⭐️ Star！
