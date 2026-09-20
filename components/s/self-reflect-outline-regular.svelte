<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uy91f4czm"/><path class="y07a50u1t"/><path class="an_usn22t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:self-reflect-outline-regular" {...props}></Icon>
<style>
:global(.an_usn22t) {
  d: path("M10.73 21.72a3 3 0 1 1 2.54 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uy91f4czm) {
  d: path("M13.69 2.37a4 4 0 1 1 -3.38 0");
}

:global(.y07a50u1t) {
  d: path("M5 13h14");
}

</style>
