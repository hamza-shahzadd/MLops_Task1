git clone <repository-url>
cd <repository-name>
git checkout -b dev
git checkout -b test
git checkout -b master
git checkout -b 20i-0796
mkdir Mlops_Project
cd Mlops_Project
touch main.py
New-Item main.py -type file
git push origin dev
git add .           
git commit -m "Your commit message"

