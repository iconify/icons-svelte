<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x6zfq7bwe"/><path class="hcagkdbmg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:signal-edge" {...props}></Icon>
<style>
:global(.hcagkdbmg) {
  d: path("M13.5 7.5H16v13h-2.5Zm5.25-4h2.5v17h-2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x6zfq7bwe) {
  fill: currentColor;
  d: path("M3 15.5h2.5v5H3Zm5.25-4h2.5v9h-2.5Z");
}

</style>
