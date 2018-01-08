<template>
  <div id="app">
    <div class="app-header">
      <div class="header-content">
        <img style="width: 50px;height: 50px" src="./assets/logo.png">
        <ul class="nav-list">
          <li>登录</li>
          <li>注册</li>
          <li>关于</li>
        </ul>
      </div>
    </div>
    <div class="app-content">
      i am content
    </div>
    <div class="app-footer">
      <p>© 2016 fishenal MIT</p>
    </div>


  </div>
</template>

<script>
  export default {}
</script>

<style lang="scss">
  #app {
    .app-header {
      .header-content {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 75px;
        background: #363636;
      }
      .nav-list {
        display: flex;
        font-size: 14px;
        color: grey;
        li {
          padding: 0 10px;
        }
        li:nth-child(1) {
          border-right: 1px solid grey;
        }
        li:nth-child(2) {
          border-right: 1px solid grey;
        }
      }
    }
    .app-footer {
      height: 80px;
      line-height: 80px;
      text-align: center;
      background: #e3e4e8;
    }
  }

</style>
