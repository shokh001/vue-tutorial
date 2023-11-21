<template>
  <div class="container">
    <h1>Counter : {{ counter }}</h1>
    <button @click="onIncrement" class="btn btn-success">ADD</button>
    <button @click="onDecrement" class="btn btn-danger">Minus</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      counter: 0,
    }
  },

  methods: {
    onIncrement() {
      this.counter +=1
    },
    onDecrement() {
      this.counter -=1
    }
  }
}
</script>

<style></style>