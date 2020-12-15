<template>
  <Foo />
</template>

<script>
import Foo from './outer/Foo.vue'
export default {
  components: { Foo }
}
</script>
