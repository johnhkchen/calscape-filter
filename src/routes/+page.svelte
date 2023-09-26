<!-- YOU CAN DELETE EVERYTHING IN THIS PAGE -->

<script lang="ts">
	import { RangeSlider } from '@skeletonlabs/skeleton';
	let value = 15;
</script>

<div class="container h-full mx-auto flex justify-center items-center">
	<div class="space-y-5">
		<h1 class="h1">Let's get cracking bones!</h1>
		<RangeSlider name="range-slider" bind:value={value} max={25} step={1} ticked />
		<h2 class="h2">The value is {value}</h2>
	</div>
</div>
