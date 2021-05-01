
<template>
 <div id="app">
   <todo todo_title="MY TODO LIST"/>
 </div>
</template>

<script>
// モジュール名をtodoではなくTodoList
import TodoList from './components/Todo.vue'

export default {
 name: 'App',
 components: {
   'todo': TodoList // 'todo'の部分は省略できる。省略するとモジュール名がコンポーネントを使う際のタグになる
 }
}
</script>

<style>
</style>