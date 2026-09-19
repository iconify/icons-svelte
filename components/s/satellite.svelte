<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m4elzebub"/><path class="z-1r63ets"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:satellite" {...props}></Icon>
<style>
:global(.m4elzebub) {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M26.736 22.723a3.2 3.2 0 1 1-4.224-1.625a3.2 3.2 0 0 1 4.224 1.625Z");
}

:global(.z-1r63ets) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.282 4.5l7.812 13m7.812 13l7.812 13");
}

</style>
