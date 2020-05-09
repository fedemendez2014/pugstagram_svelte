<script>
  import Card from "./Card.svelte";
  export let posts = [];
</script>

<style>
  .timeline {
    padding: 4em 0 0 0;
  }
</style>

<div class="timeline">
  <div class="timeline-container">
    {#each posts as post}
      <Card {...post} />
    {:else}
      <p>Loading...</p>
    {/each}
  </div>
</div>
