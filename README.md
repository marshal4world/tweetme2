# tweetme2

git init .
git add .
git remote add origin https://github.com/marshal4world/tweetme2.git
git pull --rebase origin main
git push origin main/master

python -m pipenv install django==2.2
python -m pipenv shell