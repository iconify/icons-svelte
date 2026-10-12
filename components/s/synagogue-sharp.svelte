<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="glydkqn_i"/><path class="klesinbso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:synagogue-sharp" {...props}></Icon>
<style>
:global(.glydkqn_i) {
  d: path("M2.75 21.25V5h4v6l4.7-4.25l.55-.521l.55.521l4.7 4.25V5h4v16.25Z");
}

:global(.klesinbso) {
  d: path("m12 9l2.17 3.75H9.83Zm0 5l2.17-3.75H9.83Zm-1.5 7.25v-4h3v4");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
