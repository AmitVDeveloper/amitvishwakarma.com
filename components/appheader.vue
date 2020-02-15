<template>
  <div class="app-header">
    <span class="logo">Amit</span>
  </div>
</template>

<script>
export default {};
</script>

<style>
.app-header {
  z-index: 10;
  height: 80px;
  width: 100%;
  position: fixed;
  background: linear-gradient(160deg, #00689b 0, #00adef 100%);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.06);
}

.logo {
  left: 100px;
  position: absolute;
  top: 50%;
  transform: translate(-50%, -50%);
  font-size: 24px;
  color: white;
}
</style>