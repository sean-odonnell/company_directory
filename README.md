# SigFig take home test instructions

## Step 0 - pre reqs
If you don't already have them, install brew, git, node & npm. On OSX the commands below should work.

```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew doctor #fix all issues
brew update
brew install node
brew install git
```

## Step 1 - install rest server code
```
git clone ....
npm install
```

## Step 2 - install mongodb
``` brew install mongodb ```

## Step 3 - run server
From your project folder run the following
```
mongod --dbpath data/db
npm run server
```

## Step 4 - Confirm it works, do the test
Go to http://localhost:3001/testCode/index.html . You should see the full instructions on building the app there.


## Step 6 - submit your solution
submit your entire testCode directory, and anything else you've built as a zip file back to your recruiter.

## questions/troubleshooting setup issues
Ping you're recruiter and they'll help you get it working

## Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Deploying to GitHub Pages

Run `ng github-pages:deploy` to deploy to GitHub Pages.
