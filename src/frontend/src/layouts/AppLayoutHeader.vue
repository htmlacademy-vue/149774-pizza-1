<template>
  <header class="header">
    <div class="header__logo">
      <a href="index.html" class="logo">
        <img
          src="@/assets/img/logo.svg"
          width="90"
          height="40"
          alt="V!U!E! Pizza logo"
        />
      </a>
    </div>
    <div class="header__cart">
      <a href="cart.html">0 ₽</a>
    </div>
    <div class="header__user">
      <a href="#" class="header__login"><span>Войти</span></a>
    </div>
  </header>
</template>

<script>
export default {
  name: "AppLayoutHeader",
};
</script>

<style lang="scss" scoped>
.header__login::after {
  content: "";
  display: inline-block;
  width: 32px;
  height: 32px;
  vertical-align: middle;
  background: url("~@/assets/img/login.svg") no-repeat center;
  background-size: auto 50%;
}

.header__login::after {
  margin-left: 8px;
}
</style>
