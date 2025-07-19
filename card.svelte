<!-- Card.svelte -->
<script>
  export let title;
  export let description;
</script>

<div class="card">
  <h2>{title}</h2>
  <p>{description}</p>
</div>

<style>
  .card {
    padding: 1rem;
    border: 1px solid var(--primary-color);
    border-radius: 10px;
    background-color: white;
  }
</style>