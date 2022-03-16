<template>
  <div class="navbar">
    <div class="content">
      <div class="logo">
        <a href="#">CondingJacky</a>
      </div>
      <ul class="menu__list">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Service</a></li>
        <li><a href="#">Ffeature</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.navbar {
  position: fixed;
  z-index: 5;
  width: 100%;
  padding: .1rem 0;
  background: #1b1b1b;
  .logo a {
    color: #fff;
  }
  .menu__list li a {
    color: #fff;
  }
  .content {
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
}
</style>
