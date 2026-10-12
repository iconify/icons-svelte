<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="n7x-_ubqb"/><path class="euafue3nb"/><path class="kowaom1sy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:threat-intel-sharp" {...props}></Icon>
<style>
:global(.euafue3nb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11.25q1.875-3 4.5-3c2.625 0 3.25 1 4.5 3q-1.875 3-4.5 3c-2.625 0-3.25-1-4.5-3Z");
}

:global(.kowaom1sy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11.25h.01");
}

:global(.n7x-_ubqb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l7.25 2.75v6c0 4.75-3 8.25-7.25 9.75c-4.25-1.5-7.25-5-7.25-9.75v-6Z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
