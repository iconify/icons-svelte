<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y73rjk5ux"/><path class="wpzyegbbh"/><path class="byz9m5b8d"/><path class="nx6-lsb9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wind-light-duotone-bold" {...props}></Icon>
<style>
:global(.byz9m5b8d) {
  d: path("M3 8h16");
}

:global(.nx6-lsb9m) {
  d: path("M5 15h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wpzyegbbh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 15h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y73rjk5ux) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
