<script lang="ts">
  import { Link,Router } from 'svelte-routing';
</script>

<Router>
  <Link class="bg-red-500 p-2 text-white" to="/">Home</Link>
  <Link class="router" to="test">Test</Link>
</Router>

<style>
</style>
