# React Boilerplate 2019

##### A slim, but powerful React boilerplate project

[Original Source](https://github.com/avanslaars/egghead-react-boilerplate)

## Features
* React ^16.6.1
* Webpack module bundler
* Babel to transfrom modern javascript
* Configured for both _developement_ and _production_ environments
* Generates a source map for better debugging experience
* Hot reloads
* Analyze a _production_ javascript bundle with `webpack-bundle-analyzer`
* Externalized CDN dependencies on _production_ builds
* Target specific browsers with `babel-preset-env` and the babel polyfill
* Asynchronously load webpack bundles through code-splitting and React Suspense
* Jest testing
* Prettier to automatically format code
* ESLint to avoid common javascript errors
* Run linting, tests and prettier in git hooks with Husky
* Avoid deprecated React APIs with `React.StrictMode`
* ErrorBoundary
* Check for accessibility issues in the browser with `react-axe`

## Get Started

1. Run `git clone --depth=1 git@github.com:ToddWebDev/react-boilerplate-2019.git <your-new-project-name>` to clone the repo with minimal amount of history from GitHub
2. `cd` into your new directory
3. Run `rm -rf .git` to remove current Git information so that you can add your own
4. Run `git init` to create a new Git repository
5. Add all your files with `git add .`
6. Then do a `git commit -m "Inital commit"` to commit your changes
7. Create a new repository on GitHub.com
8. Use `remote add origin` with the url in it as specified in your GitHub repo directions
9. Push to your new master with `git push -u origin master`
10. Open your `package.json` file and edit the original "name" and remove the "repository" and "bugs" attributes so that they can link to your own repository
11. Run `npm init -y` to preview changes
12. Update `readme.md`
13. 🚀Run your _deveopment_ environment with `npm run dev` to run your new react app
