<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="imoa1hb-r"/><circle class="ygphxfbhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:shapes-sharp" {...props}></Icon>
<style>
:global(.imoa1hb-r) {
  d: path("m12.55 3.58l3.9 5.84l.55.83H7l.55-.83l3.9-5.84l.55-.83zm-9.8 9.67h8v8h-8z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ygphxfbhc) {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

</style>
