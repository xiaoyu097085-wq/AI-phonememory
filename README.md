# 🎀 AI小手机 · 通用长期记忆插件（零二改版）

无需修改糯叽机、Eve 等任何 AI 小手机的代码！只要部署这个专属云端网关，就能让你的 Char 拥有**自动整理的长期记忆**，还附带一个手机端可随时修改的**“记忆小本本”**。

### 🚀 第一步：一键部署（1分钟完成）

点击下方按钮，登录 Cloudflare 账号（免费）并一路点击确认部署即可：

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/xiaoyu097085-wq/AI-phonememory)

部署完成后，你会得到一个属于自己的网址（例如：`https://ai-phonememory.xxx.workers.dev`）。

---

### 📱 第二步：接入你的 AI 小手机

打开你正在使用的 AI 小手机（糯叽机 / Eve / 酒馆等），进入 **API 设置**：
1. **接口地址（Base URL）：** 填入 `你的网址/v1`
2. **API Key：** 照常填你自己的模型 Key（如 DeepSeek Key）
3. **模型名称：** 照常填写（如 `deepseek-chat`）

---

### 📖 第三步：打开“记忆小本本”
直接在手机浏览器访问 `你的网址`（不加 `/v1`）：
* 首次打开设置一个管理密码。
* 聊天每满 **6 轮**，插件会自动在后台把你们的聊天重点提炼进记忆库，**完全不卡顿**。
* 你也可以随时在网页里手动补充纪念日、称呼或雷区，Char 下一秒对话就能读到！
