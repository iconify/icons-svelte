<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u01a_kvvb"/><path class="hq8c060ps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:whiskey-glass-sharp" {...props}></Icon>
<style>
:global(.hq8c060ps) {
  d: path("m10.72 9.25l2.81.75l.97.25l-.25.97l-.75 2.81l-.25.97l-.97-.25L9.47 14l-.97-.25l.25-.97l.75-2.81l.25-.97zM7 18h10");
}

:global(.u01a_kvvb) {
  d: path("M3.75 5.75h16.5L19 19.25l-.222 1.764L17 21H7l-1.778.014L5 19.25Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
