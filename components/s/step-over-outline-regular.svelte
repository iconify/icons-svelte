<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xyj-l9cjp"/><path class="ilnpzmblt"/><path class="b1o8mue8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:step-over-outline-regular" {...props}></Icon>
<style>
:global(.b1o8mue8c) {
  d: path("m15 11 3 3 3 -3");
}

:global(.ilnpzmblt) {
  d: path("M6 14a6 6 0 0 1 12 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
