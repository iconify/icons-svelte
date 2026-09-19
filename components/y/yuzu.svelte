<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h9uaz4fpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:yuzu" {...props}></Icon>
<style>
:global(.h9uaz4fpw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.65 4.5c-8.563 0-15.505 6.942-15.505 15.506s6.942 15.506 15.506 15.506zm4.7 39c8.563 0 15.505-6.942 15.505-15.506S34.913 12.488 26.35 12.488z");
}

</style>
