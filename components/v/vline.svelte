<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mlll53bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vline" {...props}></Icon>
<style>
:global(.mlll53bln) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.97 5.5l-17.918 37h-3.799L11.85 10.203c-.395-1.32-1.402-2.81-4.819-4.703h9.415l8.451 33.192");
}

</style>
