<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q9xl2jqoh"/><path class="nv1d-5bno"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:volunteer-application" {...props}></Icon>
<style>
:global(.nv1d-5bno) {
  d: path("M7.5 2.5h6v3h-6Zm-1 7.5l1.25 1.25L10 9m2.25 1h2.5M6.5 15H12m4 .75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

:global(.q9xl2jqoh) {
  d: path("M11.5 21.5H3V4h16v7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
