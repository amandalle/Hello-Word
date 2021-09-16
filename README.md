mkdir HelloWorld
cd HelloWorld
echo "# HelloWorld" >> README.md
git config --global user.email "amandallersdorfer@gmail.com"
git config --global user.name "Amanda Santos"
git init
git add README.mdls
git commit -m "first commit"
git branch -M main


git remote add origin https://github.com/amandalle/HellowWord.git
git push -u origin main

git log
git status
git checkout -b dev
git status

echo "print(“Hello World”)" > hello_world.py

git add hello_world.py

git commit -m "Add Hello World"
git push origin dev

git log
git checkout main
git merge dev
git push

git checkout dev
echo "print("Hello World2")" >> hello_world.py
git add .
git commit -m "Add Hello World2"
git push origin dev
