<script lang="ts">
	export let name: string;
</script>

<div>
	<main>
		<h1>Hello world!</h1>
		<p>Looks like you are up and running with Svelte.</p>
		<p>I suggest taking a look at their documentation first!</p>
	</main>
	<p class="footer">
		Made with ❤ by <a href="http://github.com/harrylovescode">HarryLovesCode</a>
	</p>
</div>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		font-size: 4em;
		font-weight: 100;
	}

	.footer {
		position: fixed;
		left: 0;
		bottom: 10px;
		width: 100%;
		text-align: center;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
