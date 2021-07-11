<template>
  <div class="counter">
    <button @click="inc()">Vue counter {{ count }}</button>
  </div>
</template>

<script>
import { ref } from 'vue'
export default {
  setup() {
    const count = ref(0)
    const inc = () => count.value = count.value + 1
    return {
      count,
      inc,
    }
  }
}
</script>
