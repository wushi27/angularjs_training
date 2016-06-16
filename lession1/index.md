##有关angularjs的概述
angularjs是一种单页面应用的解决方案。
>module

 var appModule =  angular.module('memberCenter',[]);
>controller
<code>
 appModule.controller('sidebarCtrl',function($scope,sidebarService){
    var myName = "小王";
    $scope.name = "小明";
    $scope.func  = function(){
        alert($scope.name);
        alert(myName);
    }

});
</code>