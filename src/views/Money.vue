<template>
  <div class="nav-wrapper">
    <div class="content"> Money</div>
    <Nav/>
  </div>
</template>

<script lang="ts">

export default {
  name: 'Money',
};
</script>

<style lang="scss" scoped>
.nav-wrapper {
  display: flex;
  border: 1px solid darkmagenta;
  flex-direction: column;
  height: 100vh;
}

.content {
  overflow: auto;
  flex-grow: 1;
}
</style>