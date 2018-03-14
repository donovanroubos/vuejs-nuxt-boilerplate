<template>
  <header>
    <ul class="navigation">
      <li>Home</li>
      <li>About</li>
      <li>Contact</li>
    </ul>
  </header>
</template>

<script>
//
</script>

<style lang="scss" scoped>
header {
  width: 100%;
  height: 80px;
  background: rgba(grey, 0.2);
  position: relative;
  display: block;
}
.navigation {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: flex-end;
  flex-direction: row;
  align-items: center;

  li {
    list-style-type: none;
    margin: 0 16px;
    text-transform: lowercase;
  }
}
</style>
