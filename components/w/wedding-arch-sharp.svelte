<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dn048f3af"/><circle class="ikirqmbyo"/><circle class="ac2f-b6rx"/><circle class="kas3djb3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wedding-arch-sharp" {...props}></Icon>
<style>
:global(.ac2f-b6rx) {
  cx: 7.75px;
  cy: 5.5px;
  r: 1.25px;
}

:global(.dn048f3af) {
  d: path("M5.75 21.25v-6.5a6.25 6.25 0 0 1 12.5 0v6.5m-15.5 0h18.5");
}

:global(.ikirqmbyo) {
  cx: 12px;
  cy: 4.25px;
  r: 1.5px;
}

:global(.kas3djb3j) {
  cx: 16.25px;
  cy: 5.5px;
  r: 1.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
