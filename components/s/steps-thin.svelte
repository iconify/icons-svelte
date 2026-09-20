<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="hjgamtb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:steps-thin" {...props}></Icon>
<style>
:global(.hjgamtb0n) {
  fill: currentColor;
  d: path("M244 56a4 4 0 0 1-4 4h-52v44a4 4 0 0 1-4 4h-52v44a4 4 0 0 1-4 4H76v44a4 4 0 0 1-4 4H16a4 4 0 0 1 0-8h52v-44a4 4 0 0 1 4-4h52v-44a4 4 0 0 1 4-4h52V56a4 4 0 0 1 4-4h56a4 4 0 0 1 4 4");
}

</style>
