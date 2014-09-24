# Respond.js
基于Scott Jehl的版本
添加一个方式用于media query样式转换并渲染好后回调
使用方式为：
respond.cbk.push(function(){
	alert(1);
});
respond.cbk.push(function(){
	alert(2);
});
注：cbk为一个执行队列，需要向其中添加项
其他使用与Scott Jehl的版本相同。
