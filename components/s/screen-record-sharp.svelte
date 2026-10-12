<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="s77rrwb7q"/><circle class="aehem7bjh"/><path class="guhbvob-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:screen-record-sharp" {...props}></Icon>
<style>
:global(.aehem7bjh) {
  cx: 12px;
  cy: 10.25px;
  r: 2.75px;
}

:global(.guhbvob-p) {
  d: path("M12 16.75v3.5m-3.75 0h7.5");
}

:global(.s77rrwb7q) {
  d: path("M2.75 3.75h18.5v13H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
