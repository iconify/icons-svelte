<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q6bd2y71t"/><path class="c33zbvbwu"/><path class="xlsprdnsf"/><path class="zni8d8bse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:turntable-outline-regular" {...props}></Icon>
<style>
:global(.c33zbvbwu) {
  d: path("M4 13a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q6bd2y71t) {
  d: path("M3 5v16h18V5Z");
}

:global(.xlsprdnsf) {
  d: path("M9 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.zni8d8bse) {
  d: path("m18 8 -4 4");
}

</style>
