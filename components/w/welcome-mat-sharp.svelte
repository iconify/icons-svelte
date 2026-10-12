<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u-zpycb3u"/><path class="jlabapb-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:welcome-mat-sharp" {...props}></Icon>
<style>
:global(.jlabapb-l) {
  d: path("m8.25 16.75l1.125-1.875L10.5 16.75l1.125 1.875l1.125-1.875l1.125-1.875L15 16.75");
}

:global(.u-zpycb3u) {
  d: path("M5.25 11.5V2.75h13.5v8.75m-10.5 1.75h9l.67 1.34l2.16 4.32l.67 1.34H3.25l.67-1.34l2.16-4.32l.67-1.34z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
