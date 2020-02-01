# ReactJS-GettingStarted
 If you are following the "Learn React JS - Full Course for Beginners" from freeCodeCamp.org, and you don't have SCRIMBA subscription, I have provided you the simplest way to get started in the branch "bareBones-reactApp" so you can follow the tutorials.

## What you need to do
--------------------
* Create a "my-app" directory with the following 4 files or the same name and contents:
  * package.json
  * package-lock.json
  * src/index.js
  * public/index.html
* Open the "my-app" directory in your terminal and call `npm start`, and voilà!

#### How did I create this
--------------------
* To create this repo, I started with a blank Github repo directory and then added a React .gitignore file to it, copied from [here](https://github.com/facebook/react/blob/master/.gitignore)
* Then I followed [these steps](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app) create my first react act as shown below
* Inside my GitHub repo directory, I opened it in the terminal and performed `npx create-react-app my-app`
  * If you get a message saying "command not found" in your terminal, you need to install some stuff first. If you want to use the terminal then get homebrew first `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` which takes a while, and then get node `brew install node`
  * Make sure that it works by trying `node -v` or `npm -v` or `npx -v`
  * Note that you can open terminal in VS Code using `control+``
* Then jump into the directory of your "my-app" using `cd my-app` and then build the website using `npm start`
* And it popped open my browser with the spinning react icon.
* And then inside the terminal, press `control+C` to stop the build from running 