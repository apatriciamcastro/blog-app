<template>
  <div>
   <h3>Welcome to button count application</h3>
   <p>Button count: {{ count }}</p>
   <button @click="increaseCount">Add</button>
  </div>
</template>

<script>
export default {
  data () {
    return {
      count: 0
    }
  },
  methods: {
    increaseCount () {
      this.count += 1
    }
  }
}
</script>
