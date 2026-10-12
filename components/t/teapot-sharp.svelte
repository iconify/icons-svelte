<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jp59dobhf"/><circle class="hjru5mbwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:teapot-sharp" {...props}></Icon>
<style>
:global(.hjru5mbwv) {
  cx: 12px;
  cy: 4px;
  r: 1.25px;
}

:global(.jp59dobhf) {
  d: path("M5.75 12.5a6.25 6.25 0 0 1 12.5 0v7.75H5.75v-4.5Zm0 1.75l-3-3.25m15.5-.5h.5a2.5 2.5 0 0 1 0 5h-.5M7 10.25h10");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
