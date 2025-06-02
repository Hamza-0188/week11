echo "going to setup"
git init
git  branch - m develop
mkdir ./src ./styles ./assets ./bin 
touch ./.gitignore ./src/index.html ./styles/index.css
git config --local user.name "Hamza Dogar"
git config --local user.email "l1s22bsse0188@ucp.edu.pk"
git config --local core.editor notepad 
git remote add origin https://github.com/Hamza-0188/week11.git

echo "Repository Set is complete"