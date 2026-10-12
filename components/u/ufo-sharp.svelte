<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xeg8dccjs"/><path class="m4me38btr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ufo-sharp" {...props}></Icon>
<style>
:global(.m4me38btr) {
  d: path("M7.5 9.16a4.5 4.5 0 0 1 9 0a9.25 3.25 0 0 0-9 0Zm1 9.09l-1 3m4.5-3v3m3.5-3l1 3");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xeg8dccjs) {
  d: path("M2.75 12a9.25 3.25 0 1 0 18.5 0a9.25 3.25 0 1 0-18.5 0Z");
}

</style>
