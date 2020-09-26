<template>
  <div id="app">
    <Todos />
  </div>
</template>

<script>
import Todos from "./components/Todos";
export default {
  name: "App",
  components: {
    Todos,
  },
  data() {
    return {
      todos: [
        {
          id: 1,
          value: "Do One",
          completed: false,
        },
        {
          id: 2,
          value: "Do Two",
          completed: false,
        },
        {
          id: 3,
          value: "Done Three",
          completed: true,
        },
      ],
    };
  },
};
</script>

<style>
*::before,
*::after,
* {
  padding: 0;
  margin: 0;
}
</style>
