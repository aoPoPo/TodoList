<template>
  

  <div id="app" class="container">
    <div class="Todo">
      Todo List
    </div>
    <todo-list></todo-list>
  </div>
  

</template>

<script>
import HelloWorld from "./components/HelloWorld";
import TodoList from "./components/TodoList";

export default {
  name: "App",
  components: {
    HelloWorld,
    TodoList
  }
};
</script>

<style>



.container {
  max-width: 900px;
  margin: 0 auto;
  border-radius: 8px;
  position: relative;
  padding: 0px 0px 20px 0px;
   align-items: center;
  
}

#app {
  font-family: 'Quicksand', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;

  font-size: 24px;
}

.Todo {
  background-color: #212020;
  color: #fff;
  font-size: 36px;
  font-weight: 900;
  max-width: 100%;
  margin-bottom: 40px;
  text-align: center;
  border-radius: 8px;
  position: relative;
  user-select: none;
  font-family: 'Quicksand', sans-serif;;
}
</style>
