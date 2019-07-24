- 命名空间 name space
    Phaser { }  
    1. 申明领地
    取名字  var MIUI = {}
    MIUI.version = '10.1';
    MIUI.openSystem = function() {  }
    游戏框架 最小化入侵我们的window 
    污染全局的命名空间
    2. var Phaser = {} 挂在到window下  称为作用域 scope
    window => 
    3. es5里面 类的构造 使用function（）{ }
    如果函数名首字母大写，我们就称之为类   构造函数 
    方法 Phase。Game。prototype。gameName   原型上添加任何的方法
    