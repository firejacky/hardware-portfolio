硬件工程师求职作品集

这是一个无构建步骤的静态单页网站，可直接部署到 GitHub Pages。

## 本地预览

直接双击 `index.html` 即可在浏览器打开。若浏览器限制本地字体加载，页面仍可正常显示。

## 需要先替换的内容

1. 在 `index.html` 中搜索“待填写”，替换为姓名、目标城市、联系方式和真实经历。
2. 按实际项目补充每个项目的背景、负责内容、硬件方案、测试/调试和成果。不要保留无法在面试中说明的技能或结论。
3. 将真实 PDF 简历放在此文件夹并命名为 `resume.pdf`，下载按钮会自动指向它。
4. 如需项目照片或原理图，建议建立 `assets/` 文件夹，并只上传不涉密的裁剪/脱敏图片。

## 免费发布到 GitHub Pages

1. 登录 GitHub 后新建一个公开仓库，例如 `hardware-portfolio`；不要勾选初始化 README。
2. 上传本文件夹内的 `index.html`、`styles.css`、`script.js`，以及可选的 `resume.pdf` 和 `assets/`。
3. 进入仓库的 **Settings → Pages**，在 **Build and deployment** 选择 **Deploy from a branch**，分支选 `main`、目录选 `/(root)`，然后保存。
4. 等待 GitHub 发布完成后，在同一页打开网站地址。通常链接形式为：`https://你的用户名.github.io/hardware-portfolio/`。
5. 发布后用手机打开一次，确认联系人、简历下载和项目内容无误，再生成二维码放进简历。

## 安全提醒

公开网站不要上传公司保密资料、完整生产图纸、客户信息、源码或未脱敏的内部测试数据。
