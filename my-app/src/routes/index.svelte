<script context="module">
	export const prerender = true;
</script>

<script>
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>Welcome</title>
</svelte:head>

<section>
	<h1>
		<div class="CalPic">
			<picture>
				<source srcset="cal-welcome.webp" type="image/webp" />
				<img src="cal-welcome.png" alt="Welcome" />
			</picture>
		</div>

		to my random default<br />landing page.
	</h1>

	<h2>
		For now, I have a random counter that comes with the default page.
	</h2>

	<Counter />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}


</style>
