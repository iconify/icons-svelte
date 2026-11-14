<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="linob4bwz"/><path class="m8i79gbtl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:stepper-number" {...props}></Icon>
<style>
:global(.linob4bwz) {
  d: path("M2.5 6.5h19v11h-19Zm5.5 0v11m8-11v11M4 12h2.5m11 0H20m-1.25-1.25v2.5");
}

:global(.m8i79gbtl) {
  d: path("m11 10l1.25-1v6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
