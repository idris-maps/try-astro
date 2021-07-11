<script>
  let count = 0
  const inc = () => count = count + 1
</script>

<button on:click={inc}>Svelte counter {count}</button>
