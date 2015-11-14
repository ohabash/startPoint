# Frontend startPoint
Grunt / scss / compass

#The Setup

1. clone this project to your machine or server
2. install the dependencies from package.json - from the project root

  ```
  npm install
  ```
3. run default grunt tasks defined in Gruntfile.js

  ```
  grunt
  ```
4. open your site on

 ```
  http://localhost:8000/
  ```


##

- Now your saves will trigger livereload. Probably cant have this in our environment. but it is cool :) .... if everything is working you can test it by changing a scss file and note the differnce on index.html

* when ready for production run 

  ```
  grunt build
  ```

 to turn on minification and other launch tasks