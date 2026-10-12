<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="he5c93l6x"/><circle class="r6uvok62f"/><circle class="pp3v195nj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tag-tracker-sharp" {...props}></Icon>
<style>
:global(.he5c93l6x) {
  d: path("M9.5 7.25v-2a2.5 2.5 0 0 1 5 0v2");
}

:global(.pp3v195nj) {
  cx: 12px;
  cy: 14px;
  r: 3px;
}

:global(.r6uvok62f) {
  cx: 12px;
  cy: 14px;
  r: 7.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
