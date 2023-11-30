<script>
  export let data;
</script>

<body>
<ul>
  {#each data.tech_blog as blog}
    <h1>{blog.title}</h1>
    <h2>{blog.summary}</h2>
    <p>{blog.tags}</p>
    <p>{blog.markdown}</p>
    <p>{blog.author}</p>
    
  {/each}
</ul>
</body>

<style>
  body {
    background-color: aquamarine;
    border-bottom: 100%;
    font-family: 'Courier New', Courier, monospace;
  }
</style>


  








