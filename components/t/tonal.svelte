<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ap3gi9bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tonal" {...props}></Icon>
<style>
:global(.ap3gi9bca) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 28.875l-9.75 9.75l-9.75-9.75L24 9.375l19.5 19.5l-9.75 9.75z");
}

</style>
