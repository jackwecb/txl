# 通讯录Duo 静态说明页

只有一个网页文件 `index.html`，无需安装依赖或服务器程序。将它放在 GitHub Pages 发布目录的根目录即可。

如果使用 `jackwecb/txl` 仓库：在 GitHub 仓库的 **Settings → Pages** 中选择 **Deploy from a branch**，分支选 `main`，目录选 `/ (root)`。将 `index.html` 放在该分支根目录后，预期地址是 `https://jackwecb.github.io/txl/`。仓库名称或分支不同则按实际设置调整。

| 内容 | 中文链接 | 英文链接 |
| --- | --- | --- |
| 隐私政策 | `https://<发布地址>/?page=privacy&lang=zh` | `https://<发布地址>/?page=privacy&lang=en` |
| 用户协议 | `https://<发布地址>/?page=terms&lang=zh` | `https://<发布地址>/?page=terms&lang=en` |
| 联系我们 | `https://<发布地址>/?page=contact&lang=zh` | `https://<发布地址>/?page=contact&lang=en` |

未指定 `lang` 时跟随浏览器语言，未指定 `page` 时显示隐私政策。非法参数会回退到隐私政策。网页不加载外部脚本、字体或图片。

发布前请核对发布者名称、邮箱、生效日期，以及政策描述是否与最终上架版本一致。若托管平台改变，请检查“本网页与联系”段落。App Store Connect 中的隐私政策网址应指向 `page=privacy`；支持网址应指向 `page=contact`。App 内也应提供隐私政策入口。
