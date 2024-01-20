<script lang="ts">
	import { goto } from "$app/navigation";
	import { base } from "$app/paths";
</script>

<button on:click={() => goto(`${base}/`)}>Home</button>
<button on:click={() => goto(`${base}/about`)}>About</button>
<button on:click={() => goto(`${base}/demo`)}>Demo</button>

<slot />
