<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p9_bc8bri"/><path class="us-09pbdx"/><path class="b4e05pbbe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sunlight-window" {...props}></Icon>
<style>
:global(.b4e05pbbe) {
  d: path("m9.25 14.75l-4 4");
}

:global(.p9_bc8bri) {
  d: path("M2.5 2.5h19v19h-19Zm9.5 0v19M2.5 12h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.us-09pbdx) {
  fill: currentColor;
  d: path("M14.75 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
