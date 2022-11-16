 
<!DOCTYPE html>
<html>
<head>
<title></title>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.2.5/angular.min.js"></script>
 
</head>
<body ng-app>
 
<input type="number" ng-model="tablename">
 
<p ng-repeat="i in [1,2,3,4,5,6,7,8,9,10]">
  {{ tablename }}  * {{i}} = {{tablename*i}}  <br>
</p>    
 
</body>
</html>
