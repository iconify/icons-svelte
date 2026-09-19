<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t4ea9fdcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zkb-banking" {...props}></Icon>
<style>
:global(.t4ea9fdcu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.9 43.5L8.5 24L20.9 4.5h18.6L27.1 24l12.4 19.5z");
}

</style>
