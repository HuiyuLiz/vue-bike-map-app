<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-half-transparent">
    <div class="container">
      <div
        class="d-flex justify-content-between align-items-center w-100"
      >
        <div class="navbar-nav">
          <li class="nav-item">
            <a
              class="nav-link navbar-toggle"
              aria-current="page"
              href="#"
            />
          </li>
        </div>
        <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a
              class="nav-link navbar-logo"
              aria-current="page"
              href="#"
            />
          </li>
        </ul>
        <ul class="navbar-nav">
          <li class="nav-item">
            <a
              class="nav-link text-white px-3"
              href="#"
            >探索地圖</a>
          </li>
          <li class="nav-item">
            <a
              class="nav-link text-white px-3"
              href="#"
              tabindex="-1"
            >單車活動</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.navbar-logo{
  display: block;
  width: 300px;
  min-height: 4rem;
  background: url('../assets/images/logo.svg');
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
}
.navbar-toggle{
  display: block;
  width: 100px;
  min-height: 4rem;
  background: url('../assets/images/menu_btn.svg');
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
}

.nav-background{
 background: url('../assets/images/banner.jpg');
}

.bg-half-transparent{
  background:  rgba(255, 255, 255, 0.1);
}
</style>
