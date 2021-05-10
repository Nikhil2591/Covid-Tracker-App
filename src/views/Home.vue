<template>
  <div class="home">
    Hello World
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {},
  methods: {
    async fetchCovidData(){
      const res = await fetch('')
    },
    
  },
  created() {
    
  }
}
</script>
