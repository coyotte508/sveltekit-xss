<script lang="js">
  let text = `test'"></textarea><script` + `>alert('BIM');</sc` + `ript>`;
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<textarea bind:value={text} />