<template>
  <div class="home">
    <Button label="test" />
  </div>
</template>

<script>
// @ is an alias to /src
import Button from '@/stories/buttons/Button.vue'

export default {
  name: 'Home',
  components: {
    Button
  }
}
</script>
