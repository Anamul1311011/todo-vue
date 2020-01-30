<template>
  <div id="app" class="container">
    <h1 class="title-top">todos</h1>
    <todo-list></todo-list>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import TodoList from './components/TodoList'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TodoList,
  }
}
</script>

<style>
.{
  box-sizing:border-box;
}
.container{
  max-width: 600px;
  margin: 0 auto;
}
.logo{
display: block;
margin: 20px auto;
height: 75px;
}
.title-top{
  color:#EADCDF;

}
.container h1{
  font-size: 80px;
  margin: 0;
  padding: 0;
  font-family:'Playfair Display', serif;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  font-size: 24px;
}
</style>
