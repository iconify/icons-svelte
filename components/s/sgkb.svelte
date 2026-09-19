<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qgodce3ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sgkb" {...props}></Icon>
<style>
:global(.qgodce3ad) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.115 24l11.26 18.5h20.51L28.625 24l11.26-18.5h-20.51z");
}

</style>
