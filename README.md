# mike_lab1
new mike lab

repo
gitgnore - node
readMe
license, GNU3

chatGTP

adding emoji on github :
node package manager (npm)

(read me sould be how to read and interpret code)

-- for VScode
open new terminal, getbash
cd desktop (nav to correct directory)
git clone link for repo
(get github repo code link ^)
ls
cd to repo name (mike_lab1)
git pull to get up to date
open folder, could also do code .(will open the directory)
npm i express (to chec npm info express version)
 - should get packages, might try npm i nodemon
npm init -y
 - initialize node project, will get package.json

creating file 
touch app.js
express npm code, or just copy from his repo

------------------------------------------
const express = require('express')
const app = express()

app.get('/', (req, res) => {
  res.send('Hello World This is Barry 2!')
})

console.log('in the node console');


app.listen(3000, () => {
    console.log(`Example app listening on port 3000`)
 })
-----------------------------------------------------

node app.js, to be able to run
check in brower localhost:3000
 - if there's a firewall just accept
 - if wanting to make a change can do crtl c to exit out

git status, branch main and untracked
 - need to move over into staging
git add app.js package.json package-json.js
 - can do a tab p tab (adds the words in)
 - could also do git add . (to do all)
 git commit -m 'put commit msg here'
git push, may ask to sign in

can check github and refresh, should have all files
with the commit message typed earlier
sign into render, open up
new, webservise, open repo
envirn - node
buidl cmd - yarn
start cmd - node app.js
create new webap
wait for it to deploy

deployment failed?
make sure express shows up in package json

need to refactor
 - const port copy from his app.js
adding other code PORT
(pulls up meme, going ot test it nbow right?)
node app.js
cancel out
get stauts
git add app.js
git commit -m 'refactor for env port var'
git push

back to render
should delpoy
take link form deployment (where locahost used to be)
add to repo about

 - looking into heroku big fixes 
 - how to deploy app.js link


can use nano to do html
<!DOCTYPE html>
<html lang='us'>
	<metacharset="UTF-8">

...

can use  vim (more nervous here than any point on tues)



node -v

