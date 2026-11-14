<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l3imynb0j"/><path class="b27_3kbhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sim-card-travel" {...props}></Icon>
<style>
:global(.b27_3kbhb) {
  d: path("M9 11h6v6H9Zm0 3h6");
}

:global(.l3imynb0j) {
  d: path("M6 3.5h8l4 4v13H6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
