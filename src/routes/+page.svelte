<script>
	import { Button } from '$lib/components/ui/button';
	import logo from '$lib/img/logo.svg';
	import { Facebook, Instagram } from 'lucide-svelte';
	import whatsapp from '$lib/img/whatsapp.svg';
	import tiktok from '$lib/img/tiktok.svg';
</script>

<div class="flex h-full w-full flex-col items-center justify-center gap-5 font-urbanist">
	<div class="flex flex-col items-center justify-center gap-5">
		<img class="w-28 md:w-32" src={logo} alt="logo obsidian" />
		<h1 class="font-bold text-white">Obsidian Studio 3D</h1>
	</div>
	<div class="flex w-full flex-col items-center justify-center gap-5">
		<Button
			href="https://shopee.com.br/obsidianstudio?uls_trackid=514e78a700lr"
			variant="ghost"
			class="w-3/5 rounded-3xl bg-[#7657FA] text-sm font-semibold text-white hover:bg-transparent hover:bg-gradient-to-t hover:from-[#4A018E] hover:to-[#7702E5] hover:font-bold hover:text-white md:w-1/5"
			>Loja na Shopee</Button
		>
		<!-- <Button
			variant="ghost"
			class="w-3/5 rounded-3xl bg-[#7657FA] text-white hover:bg-transparent hover:bg-gradient-to-t hover:from-[#4A018E] hover:to-[#7702E5] hover:font-bold hover:text-white md:w-1/5"
			>Loja na Amazon</Button
		> -->
		<!-- <Button
			variant="ghost"
			class="w-3/5 rounded-3xl bg-[#7657FA] text-white hover:bg-transparent hover:bg-gradient-to-t hover:from-[#4A018E] hover:to-[#7702E5] hover:font-bold hover:text-white md:w-1/5"
			>Loja no Facebook Marketplace</Button
		> -->
	</div>
	<div class="flex gap-4 pt-2">
		<a href="https://www.instagram.com/studio.obsidian/"
			><Instagram class="text-[#7657FA]" size={30} /></a
		>
		<!-- <a href="/"><Facebook class="text-[#7657FA]" size={30} /></a> -->
		<a href="https://wa.me/5555996913627?text="
			><img class="h-7 w-7" src={whatsapp} alt="whatsapp" /></a
		>
		<a href="https://www.tiktok.com/@obsidian.studio3d?_t=8qyYnhEszKf&_r=1"
			><img class="h-7 w-7" src={tiktok} alt="tiktok" /></a
		>
	</div>
</div>
