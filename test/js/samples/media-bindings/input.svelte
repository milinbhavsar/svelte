<script>
	export let buffered;
	export let seekable;
	export let played;
	export let currentTime;
	export let duration;
	export let paused;
	export let volume;
	export let playbackRate;
	export let seeking;
	export let ended;
</script>

<audio bind:buffered bind:seekable bind:played bind:currentTime bind:duration bind:paused bind:volume bind:playbackRate bind:seeking bind:ended/>
