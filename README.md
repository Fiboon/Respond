# Respond.js
基于Scott Jehl的版本<br />
添加一个方式用于media query样式转换并渲染好后回调<br />
使用方式为：<br />
respond.cbk.push(function(){<br />
	alert(1);<br />
});<br />
respond.cbk.push(function(){<br />
	alert(2);<br />
});<br />
注：cbk为一个执行队列，需要向其中添加项<br />
其他使用与Scott Jehl的版本相同。
