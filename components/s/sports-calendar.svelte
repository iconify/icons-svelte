<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e-xti72pq"/><path class="zwegp-bsc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sports-calendar" {...props}></Icon>
<style>
:global(.e-xti72pq) {
  d: path("M3 4.5h18V21H3Zm5-2v4m8-4v4m-13 3h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zwegp-bsc) {
  d: path("M13 13h4.5v4.5H13Z");
}

</style>
