<template>
  <div>
    <front-slide></front-slide>
    <front-nav></front-nav>
    <front-list></front-list>
    <app-footer></app-footer>
  </div>
</template>

<style>

</style>

<script>
import AppFooter from './Footer'
import FrontSlide from './FrontSlide'
import FrontNav from './FrontNav'
import FrontList from './FrontList'

export default {
  components: {
    FrontSlide,
    FrontNav,
    FrontList,
    AppFooter
  },
  ready () {},
  methods: {
  },
  data () {
    return {
    }
  }
}
</script>