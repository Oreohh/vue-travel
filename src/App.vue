<template>
  <div id="app">
<!--    存到内存中，无需重复ajax请求.exclude="Detail,去了Detail组件-->
    <keep-alive >
      <router-view/>
    </keep-alive>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>

</style>
