<template>
  <component :is="name" v-bind="$props" />
</template>

<script>
import Loading from './Loading'
import Copy from './Copy'
import ChevronDown from './ChevronDown'

export default {
  name: 'Icon',
  components: {
    Loading,
    Copy,
    ChevronDown
  },
  props: {
    name: {
      type: String,
      required: true
    }
  }
}
</script>
