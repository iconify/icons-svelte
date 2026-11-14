<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n1f9d0qaa"/><path class="lj49l8biv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vulnerable-package" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lj49l8biv) {
  d: path("M3.5 6L10 9.5L16.5 6M10 9.5v7m8-1.75v3.5M18 21h.01");
}

:global(.n1f9d0qaa) {
  d: path("m10.83 2.947l4.75 2.557a1.75 1.75 0 0 1 .92 1.541v4.91a1.75 1.75 0 0 1-.92 1.541l-4.75 2.557a1.75 1.75 0 0 1-1.66 0l-4.75-2.557a1.75 1.75 0 0 1-.92-1.541v-4.91a1.75 1.75 0 0 1 .92-1.541l4.75-2.557a1.75 1.75 0 0 1 1.66 0");
}

</style>
