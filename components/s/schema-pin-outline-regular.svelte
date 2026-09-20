<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hk-jkdb0v"/><path class="ah8uvpf1o"/><path class="e6q34etyy"/><path class="g22ksobnl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:schema-pin-outline-regular" {...props}></Icon>
<style>
:global(.ah8uvpf1o) {
  d: path("M3 10h13");
}

:global(.e6q34etyy) {
  d: path("M16 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.g22ksobnl) {
  d: path("M19 14v4");
}

:global(.hk-jkdb0v) {
  d: path("M3 8a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
