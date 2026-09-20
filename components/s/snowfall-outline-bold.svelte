<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uof3uv2_w"/><path class="uadcs425n"/><path class="uih_zvhtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:snowfall-outline-bold" {...props}></Icon>
<style>
:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uadcs425n) {
  d: path("M16 10.5v7m-3.5 0 7 -7");
}

:global(.uih_zvhtv) {
  d: path("M4 21h16");
}

:global(.uof3uv2_w) {
  d: path("M8 3.5v7m-3.5 0 7 -7");
}

</style>
