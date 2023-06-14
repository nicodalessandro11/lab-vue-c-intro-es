<template>
  <div id="app">
    <header>
      <nav>
        <img id="logo-iron" src="/src/images/logo-iron.png" alt="Logo Ironhack">
        <img id="burger-menu" src="/src/images/burger.png" alt="Burger Menu">
      </nav>
    </header>
    <main>
      <div class="logo-vue">
        <img src="/src/images/vue_logo.png" alt="">
      </div>
      <div class="welcome">
        <h1>Welcome to Vue.js</h1>
      </div>
      <div class="welcome-text">
        <p>Become a coding ninja with the fastest-growing JavaScript framework</p>
      </div>
      <div class="button-awesome">
        <button>Awesome</button>
      </div>
      <div class="icons">
        <div class="icons-images">
          <img id="logo-iron" src="/src/images/USP-1.png" alt="USP 1">
          <img id="burger-menu" src="/src/images/USP-2.png" alt="USP 2">
          <img id="burger-menu" src="/src/images/USP-3.png" alt="USP 3">
        </div>

      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style lang="scss" scoped>
#app {

  header {
    nav {

      #logo-iron {
        position: absolute;
        width: 35px;
        height: 38px;
        left: 30px;
        top: 20px;
      }

      #burger-menu {
        position: absolute;
        width: 22px;
        height: 20px;
        left: 548px;
        top: 29px;
      }
    }
  }

  main {

    .logo-vue {
      position: absolute;
      width: 129px;
      height: 129px;
      left: 235px;
      top: 86px;
    }

    .welcome {
      position: absolute;
      width: 456px;
      height: 158px;
      left: 125px;
      top: 194px;

      font-family: 'Inter', sans-serif;
      font-style: normal;
      font-size: 20px;
      color: #2B2F30;
    }

    .welcome-text {
      position: absolute;
      width: 309px;
      height: 40px;
      left: 145px;
      top: 275px;

      font-family: 'Inter', sans-serif;
      font-style: normal;
      font-weight: 800;
      font-size: 14px;
      line-height: 20px;

      /* or 143% */
      display: flex;
      align-items: center;
      text-align: center;
      letter-spacing: -0.02em;

      color: #000000;
    }

    .button-awesome {
      position: absolute;
      left: 239px;
      top: 354px;

      button {
        background: #34495E;
        border-radius: 13px;
        color: #FFFFFF;
        font-family: 'Inter', sans-serif;
        font-style: normal;
        font-size: 12px;
        line-height: 20px;
        width: 121px;
        height: 31px;
      }
    }

    .icons {
      position: absolute;
      width: 600px;
      height: 312px;
      left: 0px;
      top: 450px;

      background: #39B983;

      .icons-images {
        display: flex;
        justify-content: space-between;
        margin: 0 100px;
        margin-top: 100px;
      }
    }
  }
}
</style>