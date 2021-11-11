<script>
	import { onMount } from 'svelte';

	let name = 'hello';

	onMount(() => {
		name = 'world';
	});
</script>

<h1>Welcome to {name}</h1>
