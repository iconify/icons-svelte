<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tb1s_sbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:udemy" {...props}></Icon>
<style>
:global(.tb1s_sbgm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.858 15.824v18.335A9.305 9.305 0 0 0 24 43.5a9.305 9.305 0 0 0 9.142-9.34V15.823m-18.273-5.607L24 4.5l9.131 5.716");
}

</style>
