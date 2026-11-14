<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o1jr-o3li"/><path class="g59r9obmw"/><path class="c7y8r2ibv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:store-delivery-van" {...props}></Icon>
<style>
:global(.c7y8r2ibv) {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.g59r9obmw) {
  d: path("M13.5 9h4l4 4v4h-19");
}

:global(.o1jr-o3li) {
  d: path("M2.5 17V7A1.5 1.5 0 0 1 4 5.5h9.5V17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
