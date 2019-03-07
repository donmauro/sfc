<template>
  <div class="todo-list">
    <h2>To-do List</h2>
    <ul>
      <slot><li>All done!</li></slot>
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'TodoList'
  }
</script>