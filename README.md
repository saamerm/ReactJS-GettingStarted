# ReactJS-GettingStarted
 If you are following the "Learn React JS - Full Course for Beginners" from freeCodeCamp.org, and you don't have SCRIMBA subscription, I have provided you the simplest way to get started in the branch "bareBones-reactApp" so you can follow the tutorials.

## What you need to do

1. Create a "my-app" directory and copy the following 3 files with the same name, contents and location:
  * package.json
  * src/index.js
  * public/index.html
2. Open the "my-app" directory in your terminal, run `npm install` to install the dependencies the first time, and then call `npm start` to view !

You are now ready to start following along with the video tutorial!

Note: If you get an error in your terminal saying "command not found", then you need to install `npm` as shown below

#### Steps to install "npm"

"npm" is Node Package Manager, which is needed to build you React apps, and has tons of uses in Software Development today.

* You can either install it from npmjs.com/get-npm, or if you are lazy like me, you can download it from your terminal like this:
  * Get homebrew first `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` which takes a while, and then get node `brew install node`
  * Make sure that it works by trying `node -v` or `npm -v` or `npx -v`
  * Note:You can open terminal in VS Code using `control+``

#### How did I create this

* To create this repo, I started with a blank Github repo directory and then added a React .gitignore file to it, copied from [here](https://github.com/facebook/react/blob/master/.gitignore)
* Then I followed [these steps](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app) create my first react act as shown below
* Inside my GitHub repo directory, I opened it in the terminal and performed `npx create-react-app my-app`
  * If you get a message saying "command not found" in your terminal, you need to install `npm` first, as shown above
* Then jump into the directory of your "my-app" using `cd my-app` and then build the website using `npm start`
* And it popped open my browser with the spinning react icon.
* And then inside the terminal, press `control+C` to stop the build from running 