<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="i68fcw4ww"/><path class="x3tv9rxpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:teardrop" {...props}></Icon>
<style>
:global(.i68fcw4ww) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20 4l-2.14 10.41a7 7 0 1 1-8.27-8.27Z");
}

:global(.x3tv9rxpu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 13h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
