<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>模拟登录注册</title>
</head>
<body>
      <form action="" method="GET">
          <p> 账户:<input type="text" placeholder="请输入账户" minlength="5" maxlength="10"> </p>
              密码:<input type="password" placeholder="大于5位" minlength="5"> </p>
          <p> <input type="radio" name="sex">男
              <input type="radio" name="sex">女 </p>

          <select>
              <option>请选择</option>
              <option>成年</option>
              <option>未成年</option>
          </select>

          <p> <input type="button" value="注册"> </p>
          <p> <input type="reset" value="重置"> </p>
          <p> <input type="submit" value="提交"> </p>
      </form>
</body>
</html>