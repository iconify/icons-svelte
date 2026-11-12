<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpr099b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stepper-fill" {...props}></Icon>
<style>
:global(.kpr099b_q) {
  fill: currentColor;
  d: path("M5 2h14a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m2 4a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2Zm12 9v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0M3 17h6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
