# React-Portfolio
1. mkdir (create-react-app)

2. Run the project
npm i
npm start

BUild
npm run build

**Deploy React App to Github Pages**
Github
Node.js
Terminal
dev dependencies gh-pages


**Create New respository on github

<inside terminal>
npm install gh-pages --sav-dev

*Inside package.json*
add new line "honmepage": "http://{username}.github.io/{repo-name}"

*add to scripts*

"predeploy": "npm run build",
"deploy": "gh-pages -d build",
 
 
 *git init git remote add origin https://github.com/gitname/react-gh-pages.git
 
 git status*  (check the status of any commits) 
 
 git add . (add changes)
 
 git commit -m "deploy to github pages"
 
 **npm run deploy**
 
 git push -u origin master
 
 **Free Hosting **
 
 
 
 
