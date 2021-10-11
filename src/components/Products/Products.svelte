<script>
  import { onMount, onDestroy } from "svelte";

  import products from "../../stores/defaultProducts";

  
</script>

{#each $products as product}
  <h2>{product.title}</h2>
{/each}
