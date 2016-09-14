## Plotly React App

This is simple weather forecast app made in React. It was built by following along with the [Plotly Academy React tutorial series](http://academy.plot.ly/#react). The code here is for the material through chapter 3. In the future I might add the testing and the state management with Redux that is covered in the later chapters, but all of the core app functionality is present in this code.

Please Note: The once change that I made from tutorial was to remove the Open Weather Map API key from the main app code. It has been moved to a separate file that is not tracked by git, and it is then included in the main app file. If you want to use this code, be sure to create an apikey.js file in the src directory and include the following code.

```javascript
// file: src/apikey.js

module.exports = Object.freeze({
  API_KEY: 'YOUR_API_KEY_HERE'
});
```

This does **not** hide your API key from the browser (as all code runs client side), but it does keep it from being tracked on github. I'm ok with this because I am only running this code locally for practice purposes, but if you plan to run this other than locally you should come up with a more thorough solution.
