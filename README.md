"# 20220705_test" 
echo "# 20220705_test" >> README.md;
git init;
git add README.md;
git commit -m "first commit";
git branch -M main
git remote add origin https://github.com/MilersWang/20220705_test.git
git push -u origin main

新增檔案後，更新到github上
git add .
git status
git commit -m "update"
git push -u origin main

