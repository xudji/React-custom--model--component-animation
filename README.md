**自定义model弹窗组件，实现出入场动画，并通过Portals隔离样式干扰**

实现model弹窗组件的功能，主要包括四点

- 可以通过visible控制modal的显隐；
- title,content可以自定义显示内容；
- 点击取消关闭modal，同时会调用名为onClose的回调，点击确认会调用名为confirm的回调，并关闭modal，点击蒙层mask关闭modal；
- animate字段可以开启/关闭动画；