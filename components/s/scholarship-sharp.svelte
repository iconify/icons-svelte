<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b9pu7bb3q"/><circle class="pf8xrvdha"/><circle class="kp330nbbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scholarship-sharp" {...props}></Icon>
<style>
:global(.b9pu7bb3q) {
  d: path("m11.4 3.69l5.95 2.87l.9.44l-.9.44l-5.95 2.87l-.9.44l-.9-.44l-5.95-2.87l-.9-.44l.9-.44L9.6 3.69l.9-.44zM6.25 9v3.5l1.5 1.5h2.75");
}

:global(.kp330nbbl) {
  cx: 16.75px;
  cy: 16.5px;
  r: 2px;
}

:global(.pf8xrvdha) {
  cx: 16.75px;
  cy: 16.5px;
  r: 4.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
