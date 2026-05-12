<script lang="ts">
	let counter = $state(0);
</script>

<article
	class="prose h-screen max-w-none bg-linear-to-r from-slate-700 to-slate-900 text-center text-amber-100"
>
	<h1 class="py-10 text-4xl">Welcome to Toniq!</h1>
	<p>This site is currently under construction :))</p>
	<p>Check back later and see if the website is completed</p>
	<p>
		Check out the repo of this website
		<a href="https://github.com/bdonat05/toniq" class="text-blue-700 underline">here</a>
	</p>
	<p>
		Click this button not to get bored:
		<button class="rounded-sm bg-amber-100 p-1 text-blue-950" onclick={() => counter++}
			>counter: {counter}</button
		>
	</p>
</article>
