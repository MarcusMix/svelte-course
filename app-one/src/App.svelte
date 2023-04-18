<script>
	let name = 'Sandi';
	export let age;

	const incrementAge = () => {
		age += 1;
	}
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}, and my age is {age}!</h1>
<button on:click={incrementAge}>Change age</button>
