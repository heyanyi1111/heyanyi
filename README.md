# ChatGPT TopUp

这是一个用于推广 ChatGPT Plus 充值/代充服务的静态网站

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

