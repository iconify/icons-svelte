<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dldnhmbjp"/><path class="isz_u4iaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:time-tracking-sharp" {...props}></Icon>
<style>
:global(.dldnhmbjp) {
  d: path("M12 21.25A9.25 9.25 0 1 1 21.25 12");
}

:global(.isz_u4iaf) {
  d: path("M12 7.25V12l-3 2m6 6.25l2-2.5l1.75 1.5l2.5-3.75");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
