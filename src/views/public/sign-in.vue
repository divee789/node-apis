<template>
  <div class="home">
    <hello/>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "home",
  components: {
    hello:  () => import ('@/components/log'),
  }
};
</script>
