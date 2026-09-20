<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pxhtn-byk"/><path class="f5y0d7xbc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trend-down-outline-bold" {...props}></Icon>
<style>
:global(.f5y0d7xbc) {
  d: path("M17 17h4v-4");
}

:global(.pxhtn-byk) {
  d: path("m3 7 6 6 4 -4 8 8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
