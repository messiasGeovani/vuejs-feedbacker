<template>
  <component :is="name" v-bind="$props" />
</template>

<script>
import Loading from './Loading'
import Copy from './Copy'

export default {
  name: 'Icon',
  components: {
    Loading,
    Copy
  },
  props: {
    name: {
      type: String,
      required: true
    }
  }
}
</script>
