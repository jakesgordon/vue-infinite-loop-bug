<template>
  <h1>OUTER COMPONENT</h1>
  <Foo />
</template>
<script>
import Foo from '../inner/Foo.vue'
export default {
  components: { Foo }
}
</script>
