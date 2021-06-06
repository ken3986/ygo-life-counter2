<template>
  <!-- ヘッダーナビ -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a href="#" class="navbar-brand">YGO-Tools</a>
      <ul class="navbar-nav me-auto">
        <li class="nav-item">
          <NuxtLink
            to="/"
            class="nav-link"
          >
            ライフカウンター
          </NuxtLink>
        <li class="nav-item">
          <NuxtLink
            to="/change-log"
            class="nav-link"
          >
            更新履歴
          </NuxtLink>
        </li>
      </ul>
    </div>
  </nav>
</template>


<script>
export default {
  name: '',

  data () {
    return {

    }
  }, /* data */

  computed: {

  }, /* computed */

  mounted () {

  }, /* mounted */

  methods: {

  }, /* methods */

  watch: {

  }, /* watch */
}
</script>


<style>

</style>
