<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxsxtbbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:wb-twilight" {...props}></Icon>
<style>
:global(.sxsxtbbwk) {
  fill: currentColor;
  d: path("m18.35 10.1l-1.4-1.45l2.15-2.1l1.4 1.4zM2 20v-2h20v2zm9-13V4h2v3zm-5.35 3.05L3.55 7.9l1.4-1.4L7.1 8.65zM5 16q0-2.925 2.038-4.962T12 9t4.963 2.038T19 16z");
}

</style>
