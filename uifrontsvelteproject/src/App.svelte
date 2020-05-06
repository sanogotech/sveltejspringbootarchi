<script>
	
	import Inscription from './Inscription.svelte';
	export let name;
	export let username;
	let citation = 'Si vous pensez que la connaissance est chere essayez l\'ignorance';

</script>



<main>
	<h1>Hello {name}!</h1>
	<h1> Geek {username}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>

	<h3> La citation de la semaine : -- {citation}!</h3>

	<p>These styles...</p>


</main>


<Inscription>
	
	<p>These styles...</p>

</Inscription>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	p {
		color: purple;
		font-family: 'Comic Sans MS', cursive;
		font-size: 2em;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>


