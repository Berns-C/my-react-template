# my-react-template
My own react template that would help in initial creation of react app.

# TECHNOLOGIES DOCUMENTATIONS
    ReactJS: https://reactjs.org/
    Webpack: https://webpack.js.org/concepts/
    Babel: https://babeljs.io/
    Material UI: https://material-ui.com/

# Initialize package.json

	Command: npm init -y

<--------------------- DEPENDENCIES --------------------->
 # NPM React Dependencies:
	-react 			<------ React package
	-react-dom		<------ Reack DOM package

	Command: npm i react react-dom

# Material UI
    -@material-ui/core      <------ Allows to use Material UI styles
    -@material-ui/style     <------ Allows to customize Material UI using styles

    Command: npm i @material-ui/core @material-ui/style

<--------------------- DEV DEPENDENCIES --------------------->
# NPM Babel Dev Dependencies
	-@babel/core 			<------ Babel core package
	-@babel/preset-core 	<------ Allows us to run modern JS in any browser.
	-babel-loader			<------ Connects Babel to webpack.
	-@babel/preset-react 	<------ Allows us to turn JSX into plain JS.

	Command: npm i -D @babel/core @babel/preset-core babel-loader

# NPM Webpack
	-webpack                <------ Core package for Webpack
	-webpack-cli            <------ ????
	-webpack-dev-server     <------ Webpack dev server

	Command: npm i -D webpack webpack-cli webpack-dev-server


# CSS Loaders
    -css-loader         <------ Handles CSS import/require
    -style-loader       <------ Handles CSS in HTML

    Command: npm install --save-dev css-loader style-loader

# File Loader
    -file-loader    <------ resolves import/require() on a file into a url and emits the file into the output directory

    Command: npm install file-loader --save-dev
