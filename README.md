git config --global user.name "晓梦"
git config --global user.email "4718515@qq.com"
创建 git 仓库:

mkdir composer_test
cd composer_test
git init
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/wangmao2002/composer_test.git
git push -u origin master
已有仓库?

cd existing_git_repo
git remote add origin https://github.com/wangmao2002/composer_test.git
git push -u origin master
