<template>
  <div class="">
    Test
  </div>
</template>

<script>
import {useFetch} from '@nuxtjs/composition-api'

export default {
  name: 'TestComposition',
  setup() {
    useFetch(() => {})
  }
}
</script>
