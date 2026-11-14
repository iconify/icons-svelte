<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oda4a2bll"/><path class="rovth7z5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:strata-dig-layers" {...props}></Icon>
<style>
:global(.oda4a2bll) {
  d: path("M3 3.5h18v17H3Z");
}

:global(.rovth7z5f) {
  d: path("M3 9c4-2 6 2 9 0s5 2 9 0M3 14.75c4-2 6 2 9 0s5 2 9 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
