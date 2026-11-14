<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mz1avilaw"/><path class="umul83b4u"/><path class="duity9b7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sync-alt" {...props}></Icon>
<style>
:global(.duity9b7c) {
  d: path("m10.5 8l-3-3l-3 3");
}

:global(.mz1avilaw) {
  d: path("M11 4.5h2.5a3 3 0 0 1 3 3V19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.umul83b4u) {
  d: path("m19.5 16l-3 3l-3-3m-.5 3.5h-2.5a3 3 0 0 1-3-3V5");
}

</style>
