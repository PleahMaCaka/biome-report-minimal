<script lang="ts">
  import { onMount } from "svelte"
  const a = 1

  onMount(() => {
    console.log(a)
  })
</script>

<svelte:head>
    <title>blabla</title>
</svelte:head>

<h1>
    blabla title
</h1>

<div>
    blabla content
    <p>
        any more blabla content with depth
    </p>
</div>
