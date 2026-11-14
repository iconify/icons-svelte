<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t4_mf-7su"/><path class="jgwi0-wdq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:thermometer-digital" {...props}></Icon>
<style>
:global(.jgwi0-wdq) {
  d: path("M10.5 5.25h3v5h-3ZM12 13.5h.01");
}

:global(.t4_mf-7su) {
  d: path("M10 2.5h4a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-12a1 1 0 0 1 1-1Zm.75 14l.5 4c.15 1 1.35 1 1.5 0l.5-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
