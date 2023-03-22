# React-Practical-01 
## Creating an app from scratch using a flexible toolchain (using webpack from scratch ) 
<p> <b>(without use of npx create-react-app)</b> </p>

#

### For Live demo : https://react-practical-1-simform.netlify.app/
## OR 
#### (click this link to show output images) : 
https://drive.google.com/drive/folders/1J6U7TuHCQ-6_UwkAU9XT-p62_wXT6HVe?usp=sharing
#


# Directory structure
<pre>
public             : 
                    - index.html : with <b><i>`root div elements and bundle.js script`</i></b>
src                : 
                    - components : contain dummy component and it's css.
                                  - myComponent.js
                                  - myComponent.css
                    - App.js     
                    - App.css 
                    - index.js   : React-dom and render method 
                    
.gitignore         : to ensure that certain files not tracked by Git
package.json       : contains descriptive and functional metadata about a project, 
                     such as a name, version, and dependencies
                     
webpack.config.js  : contain configures of Webpack's options. (webpack option setup)
</pre>

#

<pre>
for git: two branch:
    1)"main" - main branch 
    2) "temp" - with output images and build folder (dist <- folder name)
</pre>
#

# To run the React App 

##### NOTE : to write shorter command, i change <b>`package.json`<b> file scripts object and add start & build command :
<pre>
"start": "webpack serve --mode development",
"build": "webpack --mode production"
</pre>

(you must have node installed)

### So for now we need to use following commands :

<pre>
To Installing dependencies
### `npm install`

Runs the app in the development mode.
### `npm start`

Builds the app for production to the `dist` folder.
### `npm run build`
</pre>
#


# To Creating a Toolchain from Scratch :
<pre>
A package manager, ### `npm` :
        - It use to take advantage of a vast ecosystem of third-party packages, and easily install or update them.
        
A bundler, webpack :
        - It use to write modular code and bundle it together into small packages to optimize load time.
        
A compiler such as Babel. 
        - It use to write modern JavaScript code that still works in older browsers.
        
</pre>

#

## successful output :
<img src="https://github.com/chetankochiyaniya/React-Practical-01/blob/1bc41710e820a05ac267028a572330b4fb2f6b74/output/react-app.png" alt="Practical Output Image" >
