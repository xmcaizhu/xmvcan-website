# 唯看传媒中文企业网站

## 部署步骤
1. 解压压缩包。
2. 打开 Netlify 项目，进入 Deploys。
3. 将解压后的 `xmvcan-website-cn` 文件夹拖入手动部署区域。请确认文件夹根目录直接包含 `index.html`。
4. 等待状态显示 Published，再访问站点网址。

## 文件说明
- `index.html`：首页内容
- `styles.css`：页面样式和移动端适配
- `script.js`：手机导航交互
- `success.html`：表单成功页
- `assets/favicon.svg`：网站图标
- `robots.txt`、`sitemap.xml`：基础 SEO 文件

## 表单说明
首页已配置 Netlify Forms（website-inquiry）。部署后请实际提交测试，并在 Netlify 后台 Forms 中确认收到。需要在 Netlify 后台另行设置表单通知邮箱；静态表单不会自动发送邮件。

## 绑定域名
在 Netlify 的 Domain management 添加 `www.xmvcan.com`，按页面提示配置 DNS。不要随意修改已有邮件 MX 记录。

## 修改内容
文字和联系方式在 `index.html`；颜色与布局在 `styles.css`。

案例区为设计示意，不是真实客户项目。正式宣传前请核实企业资料、联系方式和服务范围。
