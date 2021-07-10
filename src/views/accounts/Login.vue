<template>
  <div class="login">
    <div class="form-wrapper">
      <h1>用户登录</h1>
      <a-input placeholder="输入用户名" />
      <a-input-password placeholder="输入密码" />
      <a-button block>滑动验证</a-button>
      <a-button type="primary" block>登录</a-button>
      <p class="text-center">忘记密码 ｜ <span>注册</span></p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.login {
  height: 100vh;
  background: #282828;
  .form-wrapper {
    width: 360px;
    color: white;
    //   position: absolute;
    //   top: 50%;
    //   left: 50%;
    //   transform: translate(-50%, -50%);
    margin: 0 auto;
    padding-top: 200px;
    input,
    button,
    span {
      margin-bottom: 20px;
    }
    h1 {
      text-align: center;
      font-size: 22px;
      font-weight: 200;
      color: white;
    }
  }
}
</style>
