<template lang="pug">
  div
    top
    about
    application
    schedule
    workshop
    stories
    sponsors
</template>

<script>
import Top from '~/pages/Top.vue'
import About from '~/pages/About.vue'
import Application from '~/pages/Application.vue'
import Schedule from '~/pages/Schedule.vue'
import Stories from '~/pages/Stories.vue'
import Workshop from '~/pages/Workshop.vue'
import Sponsors from '~/pages/Sponsors.vue'

export default {
  components: {
    Top,
    About,
    Stories,
    Application,
    Schedule,
    Workshop,
    Sponsors
  }
}
</script>

<style lang="stylus" scoped></style>
