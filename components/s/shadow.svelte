<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zlmkv11fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:shadow" {...props}></Icon>
<style>
:global(.zlmkv11fs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.477 21.477 0 0 0 3.583 30.712a10.22 10.22 0 1 1 13.705 13.705A21.496 21.496 0 1 0 24 2.5");
}

</style>
