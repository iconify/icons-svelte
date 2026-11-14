<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gn2obmb1s"/><path class="afuxdilot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:speed-bump-sign" {...props}></Icon>
<style>
:global(.afuxdilot) {
  d: path("M7.5 17H9a3 3 0 0 1 6 0h1.5");
}

:global(.gn2obmb1s) {
  d: path("M12 2.75L21.75 20H2.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
