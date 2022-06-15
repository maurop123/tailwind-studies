<template>
  <div id="main-container" :class="`grid grid-cols-${columns}`"
      style="background:#ddd;height:600px"
  >
    <div v-for="column in columns" :key="column"
      :class="`w-full`" style="height:400px; border:1px solid #EEEEEE;background:white"
    >
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      columns: 3,
    }
  }
}
</script>
