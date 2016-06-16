##有关angularjs的概述
angularjs是一种单页面应用的解决方案。
>module

 var appModule =  angular.module('memberCenter',[]);
>controller

 appModule.controller('sidebarCtrl',function($scope,sidebarService){<br />
    var myName = "小王";<br />
    $scope.name = "小明";<br />
    $scope.func  = function(){<br />
        alert($scope.name);<br />
        alert(myName);<br />
    }<br />

});
