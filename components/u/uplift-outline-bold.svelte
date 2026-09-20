<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aut8y9hmn"/><path class="ow_ax0v9r"/><path class="du_3_4tit"/><path class="sgi0qkbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:uplift-outline-bold" {...props}></Icon>
<style>
:global(.aut8y9hmn) {
  d: path("M7 12v7");
}

:global(.du_3_4tit) {
  d: path("M4 21.5h16");
}

:global(.ow_ax0v9r) {
  d: path("M15 6v13");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sgi0qkbzh) {
  d: path("m9 10.5 3 -3");
}

</style>
