<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="li1z4j6ry"/><path class="t4hfs9bot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:statement-reconcile" {...props}></Icon>
<style>
:global(.li1z4j6ry) {
  d: path("M4.5 2.5h15v19h-15Zm3 4.5h4");
}

:global(.t4hfs9bot) {
  d: path("M13.75 7L15 8.25l2-2.5M7.5 12h4m2.25 0L15 13.25l2-2.5M7.5 17h4m2.25 0L15 18.25l2-2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
