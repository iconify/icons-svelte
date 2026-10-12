<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vf1nmycxw"/><path class="pnlsgxbav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spire-sharp" {...props}></Icon>
<style>
:global(.pnlsgxbav) {
  d: path("M10.5 19.25V15.5h3v3.75");
}

:global(.vf1nmycxw) {
  d: path("M8 20.65v-8.9l.24-.55l3.52-7.9l.24-.55l.24.55l3.52 7.9l.24.55v9.5H8zM10.5 8.5h3M8 12.75h8");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
