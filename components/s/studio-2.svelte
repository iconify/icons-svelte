<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rurgsgb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:studio-2" {...props}></Icon>
<style>
:global(.rurgsgb0e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.296 4.5L12.704 16.936v9.948l22.592-12.435zm0 16.616L12.704 33.551V43.5l22.592-12.436zm-9.065-1.677l9.065 1.677M24.23 27.207l-11.526-.323");
}

</style>
