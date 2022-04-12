<template>
  <div>Home Page</div>
  <div>{{ count }}</div>
</template>

<script>
import { useCount } from '@/composables/count';

export default {
  setu() {
    const { count } = useCount();

    return {
      count
    }
  }
}
</script>

<style>
</style>