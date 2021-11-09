# American Energy Society Industry Maps

This project was bootstrapped with
[Create React App](https://github.com/facebook/create-react-app). You'll need
`npm`/`yarn` installed to do any meaningful work on the app itself.

There is also a `pipeline/` directory containing various data preprocessing
scripts for getting the industry data ready for upload. To run those scripts,
you'll need Python 3 installed, along with `pandas` and `numpy`.

See [the wiki](https://github.com/energy-society/energy-industry-maps/wiki) for
further instructions on contributing.

## How to dev

In the project directory, run:

### `yarn install --ignore-engines`

Installs all dependencies needed to build the project.

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the
best performance.

The build is minified and the filenames include the hashes.<br />

### `yarn gh-pages -d build`

Builds the app for Github Pages. 

## Hosting on custom subdomain
1. Change the *homepage* argument of `package.json` to be the subdomain that you want.
2. After building the Github page, change the subdomain by going to *Settings>Pages* in the repo and change the custom domain.
    * Make sure that the custom domain does not have "https://" or and an ending "/" when you copy it in.
    * You may need to add the custom domain every time you rebuild the page.

<br >

FMI: https://create-react-app.dev

Collaborators: Axel, Franklyn, Lauren, Bryce