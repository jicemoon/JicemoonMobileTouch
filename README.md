# JicemoonMobileTouch

MobileTouch
一个简单的JS Mobile Touch的兼容库(兼容ios/android/wp)
包括的事件如下
tap: 轻触或点击
touchStart: 手指或鼠标按下
touchMove: 手指或鼠标按下后并移动
touchEnd:手指或鼠标抬起
swipe:手指或鼠标轻轻划过,可以通过设置对象的swipeTime修改限制时间, 默认为200ms

事件对象包含的属性
pageX/pageY: 事件发生的页面坐标
screenX/screenY: 事件发生的屏幕坐标
target: 触发事件的当前对象
touch: 当前JicemoonMobileTouch对象的引用


事件对象包含的方法:
stopPropagation: 阻止冒泡
preventDefault: 阻止浏览器默认行为
下面是touchMove/toucheEnd/swipe/tap事件对象有的属性
moveTotalScreenX/moveTotalScreenY: 
moveTotalPageX/moveTotalPageY: 
time:从触发touchStart到触发此事件经过的毫秒数
