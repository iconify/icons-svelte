<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="owwm30b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:what3words" {...props}></Icon>
<style>
:global(.owwm30b1n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9 34.91l8.18-21.82m2.73 21.82l8.18-21.82m2.73 21.82L39 13.09");
}

</style>
