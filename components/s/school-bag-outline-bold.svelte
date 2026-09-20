<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fw2qxabom"/><path class="m-p3hbclp"/><path class="s6lrl6bmb"/><path class="xwfp38btc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:school-bag-outline-bold" {...props}></Icon>
<style>
:global(.fw2qxabom) {
  d: path("M4 21V11a8 8 0 0 1 16 0v10Z");
}

:global(.m-p3hbclp) {
  d: path("M4 15h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s6lrl6bmb) {
  d: path("M9 4v3");
}

:global(.xwfp38btc) {
  d: path("M15 4v3");
}

</style>
