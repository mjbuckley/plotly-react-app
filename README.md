## Plotly React App

This is simple weather forecast app made in React. It was built by following along with the [Plotly Academy tutorial series on React](http://academy.plot.ly/#react). The code here is for the material through chapter 3. In the future I might add the testing and the state management with Redux that is covered in the later chapters, but all of the core app functionality is present in this code.

Please Note: The one change that I made from the tutorial was to remove the Open Weather Map API key from the main app code. It has been moved to a separate file that is not tracked by git, and it is then included in the main app file. If you want to use this code, you need to create an apikey.js file in the src directory and include the following code.

```javascript
// file: src/apikey.js

module.exports = Object.freeze({
  API_KEY: 'YOUR_API_KEY_HERE'
});
```

This file is already included in the .gitignore file, and the code is already set up to look for the API key here. This does **not** hide your API key from the browser (as all code runs client side), but it does keep it from being tracked by git and viewable on github. I'm ok with this because I am only running this code locally for practice purposes, but if you plan to run this somewhere other than your own computer, then you should come up with a more thorough solution.
