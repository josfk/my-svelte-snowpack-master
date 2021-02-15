<!-- App.svelte -->
<script>
  /* component logic will go here */
  import Nav from "./components/Nav.svelte";
  import List from "./components/List.svelte";
</script>

<style>
  /* css will go here */
  h1 {
    color: purple;
  }
</style>

<main>
  <div class="App">
    <Nav />
    <h1>I changed!</h1>
    <List />
  </div>
</main>
