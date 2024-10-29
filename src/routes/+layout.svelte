<script>
	import '../app.css';
	let { children } = $props();
</script>

<div
	class="h-screen w-screen bg-[#27272A] bg-gradient-to-t from-[#101011] via-[#101329] to-[#101329] pb-20"
>
	{@render children()}
</div>
