表单验证
用户名长度大于5到17
密码字母数字6到18
手机号国内手机

 const reg = {
            tel: /^1[34578]\d{9}$/,
            user: /^[a-zA-Z_]\w{5,17}$/,
            pwd: /^[\w\.+\-\/\\!@#$%\^&*\(\)\[\]|~?,:\;'"{}`<>=]{6,18}$/
  };
![image](https://github.com/MengZhaoFly/weui/blob/master/login/desc/form.png)
![image](https://github.com/MengZhaoFly/weui/blob/master/login/desc/form1.png)
