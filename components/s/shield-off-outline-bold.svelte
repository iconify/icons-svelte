<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ymp2b4b6u"/><path class="wuegxr5di"/><path class="obk7c3b6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shield-off-outline-bold" {...props}></Icon>
<style>
:global(.obk7c3b6v) {
  d: path("m14 9 -4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wuegxr5di) {
  d: path("m10 9 4 4");
}

:global(.ymp2b4b6u) {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

</style>
