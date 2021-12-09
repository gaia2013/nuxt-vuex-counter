<template>
  <section class="container">
    <div>
      <Counter></Counter>
      <hr>
      <Counter></Counter>
      <hr>
      <Counter></Counter>
      <hr>
    </div>
  </section>
</template>

<script>
import Counter from '~/components/Counter.vue'

// Counter Component が index.vue で利用できるようになる
export default {
  components: {
    Counter
  }
}
</script>
