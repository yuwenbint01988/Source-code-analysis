版本是3.0.4的，先看下面简单的例子

<!DOCTYPE html>
<html>
  <head>
    <script src="./vue.js" >
    </script>
  </head>
  <body>
    <div id="counter">
      <div>{{text}}</div>
    </div>
  </body>
</html>
<script>
  const CounterApp = {
  data() {
    return {
      text: '哈哈哈'
    }
  }
}
Vue.createApp(CounterApp).mount('#counter')
</script>



![image-20201217114247687](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20201217114247687.png)





<!DOCTYPE html>
<html>
  <head>
    <script src="./vue.js" >
    </script>
  </head>
  <body>
    <div id="counter">
      <div>{{text}}</div>
    </div>
  </body>
</html>
<script>
  const CounterApp = {
  data() {
    return {
      text: '哈哈哈'
    }
  }
}
Vue.createApp(CounterApp).mount('#counter')
</script>

