<script>
	import Tailwindcss from '../components/Tailwindcss.svelte';
	import Nav2 from '../components/Nav2.svelte';

	export let segment;
</script>

<Tailwindcss />

<Nav2 {segment}/>

<main>
	<slot></slot>
</main>