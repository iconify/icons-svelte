<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="abnm6smsv"/><path class="flr8fjbul"/><path class="q1w67xbec"/><path class="v3qgglbcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:xxe-outline-bold" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.flr8fjbul) {
  d: path("M10 9.5 7.5 12l2.5 2.5");
}

:global(.q1w67xbec) {
  d: path("m14 9.5 2.5 2.5 -2.5 2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v3qgglbcl) {
  d: path("M12 9.5v5");
}

</style>
