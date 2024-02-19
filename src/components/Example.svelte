<script lang="ts">
  let name = "john";

  /*
    The Workaround
    - Props added:
        - Local: works in MDX context
        - Remote: shows `undefined` in UI
    - Props removed:
        - Local: shows `undefined` in UI
        - Remote: shows `undefined` in UI
  */
  const {} = $props<any>();
</script>

<p>Hello {name}, this is a Svelte test component.</p>
