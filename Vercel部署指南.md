# Vercel 部署指南 - 车贷小程序进件系统

## 🚀 部署步骤（5分钟完成）

### 前置条件

✅ 代码已推送到 GitHub: https://github.com/HeavensFeel/car-loan-ui

---

## 第一步：登录 Vercel

1. 访问：https://vercel.com/signup
2. 点击 **"Sign Up"** 或 **"Login"**
3. 选择 **"Continue with GitHub"**
4. 授权 Vercel 访问你的 GitHub 账号
5. 选择用户名：`HeavensFeel`

---

## 第二步：导入项目

1. 登录后，点击顶部导航栏的 **"Add New..."**
2. 选择 **"Project"**

---

## 第三步：选择 GitHub 仓库

1. 在 "Import Git Repository" 列表中找到 `car-loan-ui`
2. 点击 **"Import"** 按钮

---

## 第四步：配置项目

保持默认配置即可：

| 配置项 | 值 |
|--------|-----|
| **Framework Preset** | Other |
| **Root Directory** | ./ |
| **Build Command** | (留空) |
| **Output Directory** | ./ |
| **Install Command** | (留空) |

**重要：** 确保 "Project Name" 为 `car-loan-ui` 或你喜欢的名称

---

## 第五步：部署

1. 点击页面底部的 **"Deploy"** 按钮
2. 等待 30-60 秒，Vercel 会自动构建和部署
3. 部署成功后，你会看到确认页面

---

## 第六步：获取公网地址

部署完成后，Vercel 会提供两个地址：

1. **生产环境地址**（主要使用）：
   ```
   https://car-loan-ui.vercel.app
   ```

2. **预览地址**（用于测试）：
   ```
   https://car-loan-ui-xyz.vercel.app
   ```

**将生产环境地址分享给你的团队伙伴即可！**

---

## 🎉 部署成功！

你现在可以：
- ✅ 在任何设备上访问 UI 系统
- ✅ 分享链接给团队伙伴
- ✅ 自动 HTTPS 加密
- ✅ 全球 CDN 加速

---

## 📱 访问地址示例

部署完成后，你可以访问：
```
https://car-loan-ui.vercel.app/index.html
```

---

## 💡 高级配置（可选）

### 自定义域名

1. 进入项目 Settings
2. 选择 "Domains"
3. 添加自定义域名，例如：`carloan.yourdomain.com`

### 环境变量

如果需要配置环境变量：
1. 进入项目 Settings
2. 选择 "Environment Variables"
3. 添加变量名和值

### 自动部署

每次推送到 GitHub，Vercel 会自动重新部署：
```bash
git add .
git commit -m "更新内容"
git push
```

---

## 🛠️ 常见问题

### Q: 部署失败怎么办？
A: 检查以下几点：
- 仓库是否为 Public
- 是否正确授权了 GitHub
- Build Command 和 Output Directory 是否正确

### Q: 如何更新部署？
A: 只需推送新代码到 GitHub，Vercel 会自动重新部署

### Q: 能否删除部署？
A: 可以，在 Vercel 项目页面点击 "Settings" → "Delete"

---

## 📊 部署优势

| 特性 | 说明 |
|------|------|
| 🚀 极速部署 | 30秒内完成 |
| 🌍 全球 CDN | 访问速度快 |
| 🔒 HTTPS | 自动安全加密 |
| 🔄 自动更新 | 代码推送即部署 |
| 🆓 永久免费 | 无需付费 |
| 📱 完美支持 | 静态网站 |

---

**现在去 Vercel 开始部署吧！5分钟后就能得到分享链接！** 🎉
