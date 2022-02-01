 <script>
   import ToDoITEM from "../lib/todo-item.svelte"


   const page_title = "Todo | New"

 </script>
<svelte:head>
  <title>{page_title}</title>
</svelte:head>


<h1>{page_title}</h1>

<form action="" method="">
  <input type="text" name="text" aria-label="Add a Todo" placeholder="+ Type to add a todo">
</form>


<ToDoITEM />
