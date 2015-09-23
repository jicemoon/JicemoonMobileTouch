# JicemoonMobileTouch

MobileTouch<br />
&nbsp;&nbsp;一个简单的JS Mobile Touch的兼容库(兼容ios/android/wp)<br />
<br />
包括的事件如下<br />
&nbsp;&nbsp;<span style="color:#ffe500;">tap:</span> 轻触或点击<br />
&nbsp;&nbsp;<span style="color:#ffe500;">touchStart:</span> 手指或鼠标按下<br />
&nbsp;&nbsp;<span style="color:#ffe500;">touchMove:</span> 手指或鼠标按下后并移动<br />
&nbsp;&nbsp;<span style="color:#ffe500;">touchEnd:</span>手指或鼠标抬起<br />
&nbsp;&nbsp;<span style="color:#ffe500;">swipe:</span>手指或鼠标轻轻划过,可以通过设置对象的swipeTime修改限制时间, 默认为200ms<br />
<br />
事件对象包含的属性<br />
&nbsp;&nbsp;<span style="color:#ffe500;">pageX/pageY:</span> 事件发生的页面坐标<br />
&nbsp;&nbsp;<span style="color:#ffe500;">screenX/screenY: </span>事件发生的屏幕坐标<br />
&nbsp;&nbsp;<span style="color:#ffe500;">target: </span>触发事件的当前对象<br />
&nbsp;&nbsp;<span style="color:#ffe500;">touch: </span>当前JicemoonMobileTouch对象的引用<br />
&nbsp;&nbsp;<span style="color:#ffe500;">下面是touchMove/toucheEnd/swipe/tap事件对象有的属性<br />
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ffe500;">moveTotalScreenX/moveTotalScreenY: </span>从touchStart触发点, 到当前事件触发点移动的屏幕距离<br />
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ffe500;">moveTotalPageX/moveTotalPageY:</span> 从touchStart触发点, 到当前事件触发点移动的页面距离<br />
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#ffe500;">time:</span>从触发touchStart到触发此事件经过的毫秒数
<br />
事件对象包含的方法:<br />
&nbsp;&nbsp;<span style="color:#ffe500;">stopPropagation: </span>阻止冒泡<br />
&nbsp;&nbsp;<span style="color:#ffe500;">preventDefault: </span>阻止浏览器默认行为<br />
