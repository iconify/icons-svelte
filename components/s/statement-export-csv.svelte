<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z34theb_m"/><path class="ejkj6th1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:statement-export-csv" {...props}></Icon>
<style>
:global(.ejkj6th1k) {
  d: path("M16.25 15.5h4.25v4.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z34theb_m) {
  d: path("M11.1 21H3V3h18v9.6M3 9h18M3 15h10.4M9 3v18m6-18v9.7m0 8.3l5.25-5.25");
}

</style>
