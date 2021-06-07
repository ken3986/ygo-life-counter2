<template>
  <div>
    <!-- ヘッダーナビ -->
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#">YGO-Tools</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">
            <NuxtLink
              to="/"
              class="nav-link"
            >ライフカウンター
            </NuxtLink>
          </b-nav-item>
          <b-nav-item href="#">
            <NuxtLink
              to="/change-log"
              class="nav-link"
            >更新履歴
            </NuxtLink>
          </b-nav-item>
        </b-navbar-nav>


      </b-collapse>
    </b-navbar>
  </div>
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
