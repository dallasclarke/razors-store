<script>
  import { link } from "svelte-routing";

  import Hero from "../components/Hero.svelte";
</script>

<Hero>
  <a href="/products" class="btn btn-primary btn-hero" use:link>Shop Now</a>
</Hero>
