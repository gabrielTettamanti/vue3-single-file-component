<template>
  <div class="hello">
    <h1 class="username">{{msg}}</h1>
      <BigYellowUsername username="gabrielTettamanti" />
  </div>
</template>

<script>
import BigYellowUsername from './BigYellowUsername.vue'
export default {
  name: 'HelloWorld',
  components: {
    BigYellowUsername
  },
  props: {
    msg: String
  },
  data () {
    return {
      showUsername: false
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
