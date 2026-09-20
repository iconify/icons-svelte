<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="p79-c2bfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:terminal-window-bold" {...props}></Icon>
<style>
:global(.p79-c2bfb) {
  fill: currentColor;
  d: path("M72.5 150.63L100.79 128L72.5 105.37a12 12 0 1 1 15-18.74l40 32a12 12 0 0 1 0 18.74l-40 32a12 12 0 0 1-15-18.74M144 172h32a12 12 0 0 0 0-24h-32a12 12 0 0 0 0 24m92-116v144a20 20 0 0 1-20 20H40a20 20 0 0 1-20-20V56a20 20 0 0 1 20-20h176a20 20 0 0 1 20 20m-24 4H44v136h168Z");
}

</style>
