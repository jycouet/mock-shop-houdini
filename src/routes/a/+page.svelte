<script lang="ts">
  import type { PageData } from "./$houdini";

  export let data: PageData;

  $: ({ Product } = data);
</script>

<pre>{JSON.stringify($Product.data, null, 2)}</pre>
