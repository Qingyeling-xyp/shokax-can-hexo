# ShokaX Can
## 开始
ShokaX 即食罐头，使用 pnpm 加热即可食用，执行下列命令：
```bash
git clone https://github.com/theme-shoka-x/shokax-can --depth=1
cd shokax-can
pnpm install
hexo s # 如果报错更换为 pnpm dlx hexo s
```

当前内容物版本：ShokaX v0.4.11 不含 lightning-minify

## 创建链接
```bash
mklink /J .\themes\shokax .\node_modules\hexo-theme-shokax # windows CMD
# 或
cd ../themes && ln -s ../node_modules/hexo-theme-shokax shokax # Linux Bash
```
随后可以通过`themes/shokax`访问主题文件

# 备注

```
如果npx hexo g 报错
重新安装pnpm install katex即可
备份hexo
git remote add origin git@github.com:Qingyeling-xyp/hexo.git
```



# OK这里是日志

## 2024/9/14  0:57

现在列表数据测试成功[hello world\ 测试 \docker]

## 2024/9/15 12:11

这次把搜索引擎搞好了,评论系统有问题 vercel 加载慢要切换国内域名

14号评论搞了一天各种都试过了

### [valine 系评论系统]

vercel 部署成功 加载慢

netlify  大成功  ohhhhhhhh!!!!!!!!!!!!!!!!!!!!!  

Railway  找不到 sql往哪里注入

Zeabur  docker镜像问题 等后续解决

腾讯云服务 懂的都懂

可以尝试独立部署

## [Twikoo]

mongoDb Atilas  注册成功 数据库创建成功  root\

Hugging Face 部署成功  但是会导致秘钥泄露 github无法部署上传

netlify  部署失败 github链接不上  后面链接上了(用的小号)   多少同hugging Face



评论这一块搞了快十小时这么点背 555555........
