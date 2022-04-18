<script lang="ts">
  import { Route,Router } from 'svelte-routing';
  import Home from './components/Home.svelte';
  import MainRouter from './components/MainRouter.svelte';
  import Test from './components/Test.svelte';

  export let url = '';
</script>

<main>
  <MainRouter />
  <Router {url}>
    <Route path="test" component={Test} />
    <Route path="/"><Home /></Route>
  </Router>
</main>

<style>

</style>
