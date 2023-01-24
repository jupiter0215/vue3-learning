<template>
  <div>
    {{ msg }} <br/> <br/>
    <button @click="count++">{{ count }}</button>
  </div>
</template>

<script>
export default {
  name: 'Counter',
  data() {
    return {
      count: 0
    }
  },
  props: {
    msg: String
  }
}
</script>
