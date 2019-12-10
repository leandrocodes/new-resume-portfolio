<template lang="pug">
  section
    .block
      b-icon(icon='account' size='is-small')
      b-icon(icon='home' size='is-small')
      b-icon(icon='view-dashboard' size='is-small')
    .block
      b-icon(icon='account')
      b-icon(icon='home')
      b-icon(icon='view-dashboard')
    .block
      b-icon(icon='account' size='is-medium')
      b-icon(icon='home' size='is-medium')
      b-icon(icon='view-dashboard' size='is-medium')
    .block
      b-icon(icon='account' size='is-large' type='is-success')
      b-icon(icon='home' size='is-large' type='is-info')
      b-icon(icon='view-dashboard' size='is-large' type='is-primary')
    button.button.is-dark
      b-icon(icon='check')
      span Finish
    button.button.is-warning
      b-icon(icon='check')
      span Finish
</template>

<script>
export default {
  name: 'HomePage',
  components: {},
  data: () => ({
    hello: 'leandro'
  })
}
</script>
