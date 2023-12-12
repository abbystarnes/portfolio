<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div>
    <img src="./src/assets/catConstruction.png" class="logo" alt="Cat Under Construction" />
  </div>
  <h1>AMS Portfolio</h1>

  <p>Under Construction</p>
  <p>
    Check out <a href="https://github.com/abbystarnes" target="_blank"> my Github </a>, in the meantime!
  </p>
</main>

<style>
  .logo {
    height: 15em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
