<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiqyvsyri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:screenshot-region-outline" {...props}></Icon>
<style>
:global(.fiqyvsyri) {
  fill: currentColor;
  d: path("M17 22v-3h-3v-2h3v-3h2v3h3v2h-3v3zM5 19v-5h2v3h3v2zm0-9V5h5v2H7v3zm12 0V7h-3V5h5v5z");
}

</style>
