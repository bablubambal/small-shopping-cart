# Getting Started To Deploy app to the Github Pages
Create a Git Repo and React Project and Follow the steps :
Copy the link of the remote origin from your accoung

# small-shopping-cart visit my live app
Open [SmallShoppingCart](https://bablubambal.github.io/small-shopping-cart) to view it in your browser.




## Step 1
git remote add origin [YOUR REPO LINK]
git add -A
git commit -m "message to commit like initital commit"
git push -u origin main


## Step 2

--> In Package.json file intigrate the following line:
`"homepage":"https://[USERNAME].github.io/[YOUR REPO NAME]`,

## Step 3

Install the package in your system
`npm install gh-pages --save-dev`

## Step 4
in Package.json add the following scrips in json file 
` "predeploy":"npm run build",
  "deploy":"gh-pages -d build",

`
### Step 5
Now Run `npm run deploy`
