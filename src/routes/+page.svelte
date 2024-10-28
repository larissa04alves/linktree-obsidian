<script>
	import { Button } from '$lib/components/ui/button';
	import logo from '$lib/img/logo.svg';
</script>

<div class="font-urbanist flex h-full w-full flex-col items-center justify-center gap-5">
	<div class="flex flex-col items-center justify-center gap-5">
		<img class="w-32" src={logo} alt="logo obsidian" />
		<h1 class="font-bold text-white">Obsidian Studio 3D</h1>
	</div>
	<div class="flex w-full flex-col items-center justify-center gap-5">
		<Button
			variant="ghost"
			class="w-1/5 rounded-3xl bg-[#7657FA] text-white hover:bg-transparent hover:bg-gradient-to-t hover:from-[#4A018E] hover:to-[#7702E5] hover:font-bold hover:text-white"
			>Loja na Shopee</Button
		>
		<Button
			variant="ghost"
			class="w-1/5 rounded-3xl bg-[#7657FA] text-white hover:bg-transparent hover:bg-gradient-to-t hover:from-[#4A018E] hover:to-[#7702E5] hover:font-bold hover:text-white"
			>Loja na Amazon</Button
		>
		<Button
			variant="ghost"
			class="w-1/5 rounded-3xl bg-[#7657FA] text-white hover:bg-transparent hover:bg-gradient-to-t hover:from-[#4A018E] hover:to-[#7702E5] hover:font-bold hover:text-white"
			>Loja no Facebook Marketplace</Button
		>
	</div>
	<div></div>
</div>
