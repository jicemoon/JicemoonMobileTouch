# JicemoonMobileTouch

MobileTouch<br />
一个简单的JS Mobile Touch的兼容库(兼容ios/android/wp)<br />
<br />
包括的事件如下<br />
    tap: 轻触或点击<br />
    touchStart: 手指或鼠标按下<br />
    touchMove: 手指或鼠标按下后并移动<br />
    touchEnd:手指或鼠标抬起<br />
    swipe:手指或鼠标轻轻划过,可以通过设置对象的swipeTime修改限制时间, 默认为200ms<br />
<br />
<br />
事件对象包含的属性: <br />
    pageX/pageY: 事件发生的页面坐标<br />
    screenX/screenY: 事件发生的屏幕坐标<br />
    target: 触发事件的当前对象<br />
    touch: 当前JicemoonMobileTouch对象的引用<br />
    <br />
    事件对象包含的方法:<br />
    stopPropagation: 阻止冒泡<br />
    preventDefault: 阻止浏览器默认行为<br />
    下面是touchMove/toucheEnd/swipe/tap事件对象有的属性<br />
    moveTotalScreenX/moveTotalScreenY: 从touchStart触发点, 到当前事件触发点移动的屏幕距离<br />
    moveTotalPageX/moveTotalPageY: 从touchStart触发点, 到当前事件触发点移动的页面距离<br />
    time:从触发touchStart到触发此事件经过的毫秒数
