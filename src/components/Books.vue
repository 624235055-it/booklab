<template>
    <div>
        
        <div v-bind:key="book.id" v-for="book in books1">
            <BookItem v-bind:book="book"/>
        </div>


    </div>
</template>

<script>
import BookItem from './BookItem.vue'
export default {
  name: 'Books',
  components: {
   BookItem
  },
  props:["books1"]
  
}
</script>

<style>
</style>