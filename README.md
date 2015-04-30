# Functions and The DOM

Try the following exercises in the browser.


## Practice With Functions

* Write a function to swap to values at two different indicies in an array.

  ```
  var swap = function (arr, indexOne, indexTwo) {
    // swap values 

    return arr;
  };
  ```

* Write a function to generate a random number in a specified range.

  ```
  var getRand = function (low, high) {
    // your work

    return randNum;
  };
  ```

* Write a function to create a specified number of random numbers from `1` to `100` in an array.

  ```
  var randArr = function (size) {
    // your work;

    return arr; 
  }
  ```

* Write a function to find the maximum number in an array.

  ```
  var getMax = function (arr) {
    // your work
    
    return max;
  }

  ```



## Playing With The DOM

Go to [generalassemb.ly](https://generalassemb.ly) and try the following exercises.

-----

*  Grab the `body` from the page using `document.querySelector`. and change the `opacity` to `.5`.

-----
* Grab all the `img` tags from the page. Iterate through each image and change the source to 

	```
http://www.maine-coon-cat-nation.com/image-files/girl-kitten-names.jpg
	```

* Create a `kittenPaint` function for your code above .Save it as a snippet in your developer console. Go to yahoo and run it there.

----

* Using 
	
	```
document.querySelectorAll("*")
	```
to grab **all elements** on the page, iterate through each `element` in the list using a `for` loop. Use 

	```
element.style.backgroundImage = "url(http://www.maine-coon-cat-nation.com/image-files/girl-kitten-names.jpg)"
	``` 

	to change every element to have a kitten background image.
* Turn the above exercise into a `kittenBomb` function and save it in `sources` under your snippets. Then run it on your favorite site.


-----

* Select the `body` from the page. When it is clicked change its style using the following, 
	
	```
body.style.transform = "rotateZ(60deg)";
	```

* Create a `click` event on the `body`.  When the body is `clicked` grab all the images on page then use the `style.transform` above to rotate each image. In other words, when the page is clicked rotate all images on the pages.





