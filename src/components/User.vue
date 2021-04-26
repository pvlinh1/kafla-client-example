
<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>

 <div v-if="seen">
    you saw me
 </div>

 <div id="app-4">
  <ol>
    <li v-for="todo in todos" :key="todo.text">
      {{ todo.text }}
    </li>
    <div v-html="rawHtml"></div>
  </ol>
</div>
  
</template>

<script>
export default {
  name: 'User',
  props: {
    msg: String
  },
  data: ()=> {
    return {
      seen: true,
      todos: [
        { text: 'Learn JavaScript' },
        { text: 'Learn Vue' },
        { text: 'Build something awesome' }
      ],
      rawHtml : "<div><h1>Vue Js Template LinhPV eat shit</h1></div>"
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
