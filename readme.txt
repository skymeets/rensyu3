
■VSC

cd D:\share\gitRensyu\dir1

git init

git config --global user.name "h-takashima"
git config --global user.email "aeroskill7@gmail.com"


echo "Hello" > test.txt

git add .\test.txt

git commit -m "test.txtファイル追加"

echo " Goodbye" >> test.txt

# 変更を取り消す
git checkout -- test.txt


echo "# rensyu3" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/skymeets/rensyu3.git
git push -u origin main


