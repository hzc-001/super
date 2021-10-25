<template>
  <div id="home">
    <nav-bar class="nav-bar">
      <div slot="center">购物中心</div>
    </nav-bar>
  </div>
</template>

<script>
import NavBar from '@/components/common/navbar/NavBar';
export default {
  components: { NavBar },
  name: 'Home',
};
</script>

<style>
#home{
  height: 100vh;
}
.nav-bar {
  background-color: var(--color-tint);
  font-weight:700;
  color: #fff;
  }
</style>
