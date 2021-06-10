<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>


<script lang="ts">
  import {add} from '$lib/test';
  let foo = add(1, 2);

  let bar: Foo = {
    bar: "bla"
  }

  console.log(bar)

</script>

{foo}
{bar.bar}
