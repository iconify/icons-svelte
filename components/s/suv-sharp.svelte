<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="arai4bb0q"/><circle class="uxwtxcbyr"/><circle class="bhnvrvjtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:suv-sharp" {...props}></Icon>
<style>
:global(.arai4bb0q) {
  d: path("M2.75 15v-4.475l1.2-.245l1.8-.36l1.8-3.06l.529-1.067L9.27 5.75H19.8l.42 1.44l.95 3.26l.08.274V16H2.75zm3-4.75h15.5m-8-4.5v4.5");
}

:global(.bhnvrvjtt) {
  cx: 17px;
  cy: 16px;
  r: 2.5px;
}

:global(.uxwtxcbyr) {
  cx: 7px;
  cy: 16px;
  r: 2.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
