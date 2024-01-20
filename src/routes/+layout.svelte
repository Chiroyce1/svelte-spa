<script>
	import { goto } from "$app/navigation";
</script>

<button on:click={() => goto("/")}>Home</button>
<button on:click={() => goto("/about")}>About</button>
<button on:click={() => goto("/demo")}>Demo</button>

<slot />
