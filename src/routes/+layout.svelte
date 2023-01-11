<script>
	import '../app.postcss';
	import '@fontsource/crete-round';
	import '@fontsource/pt-sans';
</script>

<div class="bg-gray-50 text-slate-500 grid h-screen place-content-center">
	<nav class="m-4">
		<a href="/">
			<img class="block h-12 w-auto md:hidden" src="/icon170.png" alt="Your Company" />
			<img class="hidden h-12 w-auto md:block" src="/logo.png" alt="Your Company" /></a
		>
		<a href="/process">Process</a>
	</nav>
	<main>
		<slot />
	</main>
</div>
