# Flask_app_test

To deploy a flask app on heroku.

1. Create account on herko and github
2. Download and install git and heroku cli in your pc

https://cli-assets.heroku.com/heroku-x64.exe
https://git-scm.com/download/win

1> Open anconda command prompt

to create env

conda create -n flask_app_demo python==3.7

conda activate flask_app_demo


select interpreter in pycharm project.

to install flask library cmd in given below

pip install flask

pip install gunicorn
pip freeze>requirements.txt


Create a empty "Procfile"


web: gunicorn main:app



------link github repo


echo "# flask_demo_tesing" >> README.md


git config --global user.email "<git registered mail id>"
git config --global user.name "<git user name>"
git init
git add .
git commit -m "first commit"
git branch -M main

** if error: remote origin already exists.
git remote remove origin

git remote add origin <git hub url for your repo>

ex:- git remote add origin https://github.com/PremRanjanJha/Flask_app_test.git


git push -u origin main

execute below command

heroku login -i

heroku git:remote -a heroko-flask-app05


git push heroku main
© 2021 GitHub, Inc.
