<script>
	import { browser } from '$app/env';
	import { onMount } from 'svelte';

	let name = 'hello';
	let isBrowser = false;

	onMount(() => {
		name = 'world';
		isBrowser = true;
	});
</script>

<h1>Welcome to {name}</h1>
{browser} {isBrowser}
