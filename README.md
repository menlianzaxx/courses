# courses# 克隆你的空仓库
git clone https://github.com/<你的用户名>/<仓库名>.git
cd <仓库名>

# 解压并拷贝静态站点文件到当前目录
unzip ~/Downloads/billpay_edu_static_site.zip -d .

# 提交并推送
git add .
git commit -m "Initial static site"
git push origin main
