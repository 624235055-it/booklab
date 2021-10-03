<template>
        <div class ="book-item">
            <h1>{{book.title}}</h1><br/>
            <img v-bind:src="book.thumbnailUrl"/><br/>
            <b>Author:</b>{{book.category}} <br/>
            <b>Category:</b>{{book.author}} <br/>
            <b>ISBN:</b>{{book.isbn}} <br/>
            <b>Pages:</b>{{book.Pages}} <br/>
            <b>Description:</b><br/>
            <p>{{book.shortDescription}}</p>
            
        </div>

</template>

<script>
export default {
  name: 'BookItem',
  components: {
   
  },
  props:["book"]
  
  
}
</script>

<style>
</style>