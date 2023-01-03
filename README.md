Sequence:
1. create index.html
2. create app.js
3. download angular.min.js
4. in index.html add scripts (first - angular.min.js,second - app.js)
5. in app.js create IIFE (immediately invoked function expression)
6. in IIFE create angular function: angular.module('name_of_app', []) - first attribute is name of app,second attribute is array; without semicolon in the end
7. in index.html in tag html add attribute ng-app='name_of_app'
8. add div in body of html file
9. in app.js add .controller('name_of_controller', function(){...}) - first attribute is name of controller, second attribute is function that defines functionality of controller.
10. in tag div add attribute ng-controller="name_of_controller"
11. add 'use strict' at the beginning of IIFE
12. add h1 tag 
13. add attribute $scope for controller function (all variables with dollar sign are reserved by Angular)
14. add property 'name' for variable $scope. This property is visible for our controller.
15. in double curly braces we can write this property in index.html
16. create function sayHello as a property for variable $scope
17. call this function in index.html
18. create input field in index.html
19. add special ng-model attribute to tag input with default value equal 'name'
20. add 'Inside my input is: {{name}}' in index.html to see how Angular binds the data