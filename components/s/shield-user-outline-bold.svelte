<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ymp2b4b6u"/><path class="xrw775b-m"/><path class="qjp3ou2ni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shield-user-outline-bold" {...props}></Icon>
<style>
:global(.qjp3ou2ni) {
  d: path("M8 16a4 4 0 0 1 8 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xrw775b-m) {
  d: path("M10 9.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ymp2b4b6u) {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

</style>
