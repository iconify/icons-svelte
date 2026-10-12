<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lstelzb1n"/><path class="aacqtmbqq"/><path class="gilxcj5fr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:visual-schedule-sharp" {...props}></Icon>
<style>
:global(.aacqtmbqq) {
  d: path("M13.5 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-4.75 7.25h12.5v7.5H8.75z");
}

:global(.gilxcj5fr) {
  d: path("m15 15.75l1.75 3h-3.5ZM4.75 4.5v14m-2-2l2 2l2-2");
}

:global(.lstelzb1n) {
  d: path("M8.75 2.75h12.5v7.5H8.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
