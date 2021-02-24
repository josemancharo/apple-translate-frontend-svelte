<script>
  import Apple from "./Apple.svelte";
  import Border from "./Border.svelte";
</script>

<style>
  main {
    font-family: sans-serif;
    text-align: center;
    height: 100vh;
  }
  #translate-frame {
    height: 100%;
    overflow: hidden;
  }
</style>

<main>
	<h1>Welcome to Apple Translate</h1>
	<h2>Use the Arrow Keys to translate the apple</h2>
  <h3>If it doesn't work, click the apple then try again</h3>
  <Border/>
  <div id="translate-frame">
    <Apple/>
  </div>
</main>