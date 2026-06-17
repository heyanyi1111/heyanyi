# ChatGPT TopUp

这是一个用于推广 ChatGPT Plus 充值/代充服务的静态网站，适合直接发布到 GitHub Pages。

线上访问地址：

```text
https://chongzhi.aliyuncn.com/
```

## 文件结构

```text
.
├── index.html          # 网站首页
├── 404.html            # 自定义 404 页面
├── CNAME               # GitHub Pages 自定义域名
├── robots.txt          # 搜索引擎抓取规则
├── sitemap.xml         # 网站地图
└── BingSiteAuth.xml    # Bing 站长平台验证文件
```

## 网站功能

- 响应式静态 HTML 页面，适配电脑和手机访问
- 面向中文搜索的 ChatGPT Plus 充值、代充、会员升级 SEO 文案
- Open Graph 分享信息，方便链接预览
- JSON-LD 结构化数据，包含 Organization、WebSite、Service、HowTo、FAQ
- 常见问题 FAQ，覆盖用户搜索和购买前疑问
- 自定义 404 页面
- 支持 GitHub Pages 自定义域名发布

## 发布方式

本项目不需要构建，直接推送到 GitHub 仓库即可发布。

1. 将所有文件推送到 GitHub 仓库默认分支。
2. 进入 GitHub 仓库的 `Settings > Pages`。
3. 选择默认分支和根目录作为 Pages 来源。
4. 确认 `CNAME` 文件内容为：

```text
chongzhi.aliyuncn.com
```

DNS 和 GitHub Pages 配置生效后，网站会通过以下地址访问：

```text
https://chongzhi.aliyuncn.com/
```

## 日常修改说明

- 修改首页内容、按钮链接、SEO 标题、描述、结构化数据：编辑 `index.html`
- 修改 404 页面：编辑 `404.html`
- 大幅更新页面内容后：同步更新 `sitemap.xml` 里的 `lastmod`
- 保持 `robots.txt` 中的 sitemap 地址为线上地址
- 购买卡密链接、充值中心链接、教程视频链接、客服微信信息要保持一致

## 图片说明

二维码图片当前使用原来的图片域名：

```text
https://hlplch.aliyuntm.com/chatgpt/WX20240227-105234.png
```

该图片源站有 Referer 限制，本地直接访问可能返回 403。发布到 `https://chongzhi.aliyuncn.com/` 后，浏览器带正确 Referer 请求即可正常显示。

如需本地验证图片内容，可以使用 OSS 域名访问同一路径：

```text
https://lch-hlp.oss-cn-shanghai.aliyuncs.com/chatgpt/WX20240227-105234.png
```

## 本地预览

可以使用任意静态文件服务预览，例如：

```bash
ruby -run -e httpd . -p 4173
```

然后打开：

```text
http://localhost:4173/
```

## 备注

本站是独立服务页面，与 OpenAI 无直接关联。OpenAI、ChatGPT 为其各自所有者的商标。
