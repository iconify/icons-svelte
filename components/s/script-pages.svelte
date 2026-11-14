<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g_6tshbvk"/><path class="rxpm5ub7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:script-pages" {...props}></Icon>
<style>
:global(.g_6tshbvk) {
  d: path("M3.5 5.5H17v16H3.5Z");
}

:global(.rxpm5ub7n) {
  d: path("M6.5 2.5h12a2 2 0 0 1 2 2v14m-14-9H14m-5.5 4H14m-5.5 4h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
