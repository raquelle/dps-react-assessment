8:30 am Jan 25


created a fork in github by clicking fork from

https://github.com/devpointstudios/dps-react-assessment

then I pulled the fork from the repository down to my personal computer

git clone git@github.com:raquelle/dps-react-assessment.git



this seemed to work. I looked at the version and it seemed to be linked

git remote -v origin git@github.com:raquelle/dps-react-assessment.git



I created a. env file in my root directory by typing into the terminal

`bash
cp .env.example .env`

`v code
client/src/components/beers.js`


Added a new client side route in client/src/components/App.js

import beers from './beers'
