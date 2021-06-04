<template>
  <content-Loader
    class="flex flex-col items-center rounded"
    width="100%"
    height="300px"
  >
    <content-Loader
      class="mt-3 rounded"
      width="90%"
      height="50px"
      animation-duration="2s"
    />

    <content-Loader
      class="mt-3 rounded"
      width="80%"
      height="50px"
      animation-duration="2.3s"
    />

    <content-Loader
      class="mt-3 rounded"
      width="80%"
      height="50px"
      animation-duration="2.7s"
    />

    <content-Loader
      class="mt-3 rounded"
      width="80%"
      height="50px"
      animation-duration="2.9s"
    />
  </content-Loader>
</template>

<script>
import ContentLoader from '../../components/ContentLoader'

export default {
  name: 'FiltersLoading',
  components: { ContentLoader }
}
</script>
