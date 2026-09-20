<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vtoa-gb3y"/><path class="abso_jbuo"/><path class="gxgi15ggp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:weight-goal-outline-bold" {...props}></Icon>
<style>
:global(.abso_jbuo) {
  d: path("M12 12V3");
}

:global(.gxgi15ggp) {
  d: path("M12 3h7v5h-7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vtoa-gb3y) {
  d: path("M3 14a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
