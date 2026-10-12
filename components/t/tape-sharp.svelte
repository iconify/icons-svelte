<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="bpdlsnxqj"/><path class="leyfmeqwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tape-sharp" {...props}></Icon>
<style>
:global(.bpdlsnxqj) {
  cx: 10.75px;
  cy: 10.25px;
  r: 7.5px;
}

:global(.leyfmeqwa) {
  d: path("M13.75 10.25a3 3 0 1 1-6 0a3 3 0 1 1 6 0m-3 7.5h10.5L20 19.25l1.25 1.5h-10.5Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
