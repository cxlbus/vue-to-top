# vue-to-top

![markdown](http://file.gcx365.com:8090/group1/M00/00/A3/d1ozqVv1CwOAWuMiAAAvxIhhUak127.jpg "markdown")
# 安装
> `npm install vue-to-top -S`

# 使用
**注入**
> // ES6</br>
`import vuetotop from 'vue-to-top'`</br>
> //or require</br>
`var vuetotop = require('vue-to-top')`</br>

> `Vue.use(vuetotop)`

**组件使用**
> `<vuetotop></vuetotop>`

# 参数

|    参数    |  说明   |  类型  |  可选值  |  默认值  |
| :--------: | :-----:  | :----:  | :----:  |:----:  |
| type      | 按钮的类型，一共16种   |number| 0~15  |0    |
| top | 滚动条离顶部多高时，显示返回顶部按钮 |number| 大于0的整数 |400|
| right| 按钮右部定位位置|number| 大于0的整数  |30 |
| bottom| 按钮底部定位位置|number| 大于0的整数  |30 |
| size| 按钮大小|number| 大于0的整数  |24 |
| color| 按钮颜色|string| rgb/hex  |'#666' |
| duration| 返回顶部的间隔时间 |number| 大于0的整数   |300 |
