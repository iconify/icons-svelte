<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jmolxjtwy"/><path class="j6hwip25h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:scalpel-outline-bold" {...props}></Icon>
<style>
:global(.j6hwip25h) {
  d: path("m13 12 2 2");
}

:global(.jmolxjtwy) {
  d: path("m4 20 8 -8 4 -4 3 3 -4 4 -5 5Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
