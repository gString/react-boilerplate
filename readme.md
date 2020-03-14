# React Boilerplate
>> clone:

git clone --depth=1 https://github.com/gString/react-boilerplate.git <app folder here>

>> get into folder
>> disconnect git repository (and remove history):

rm -rf .git

>> create new git repo:
git init
git add .
git commit -m "Initial commit"

>> if not on (configured) webstorm, create new repo on github and copy the commend lines from there
>> under "…or push an existing repository from the command line"

>> Changes to package.json:
>> Change the name string
>> Delete entries with repo links, ie:
>> "repository", "bugs", "homepage"
>> save and run: 
npm init -y

>> Change the readme.md, and run:
npm i
