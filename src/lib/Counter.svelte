<script>
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button on:click={increment}>
  count is {count}
</button>

<style>
  button {
    border: 1px solid #ccc;
    padding: 10px;
    margin: 10px;
  }
  button:focus {
    outline: rgb(62, 41, 41) solid 2px;
  }
</style>
