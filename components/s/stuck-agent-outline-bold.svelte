<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pf60eubcf"/><path class="mzs9lvbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stuck-agent-outline-bold" {...props}></Icon>
<style>
:global(.mzs9lvbbs) {
  d: path("M19.5 4v16");
}

:global(.pf60eubcf) {
  d: path("M11.32 7a5.5 5.5 0 1 1 -4.64 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
