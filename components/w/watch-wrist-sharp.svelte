<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zspz3p-nz"/><circle class="pfpt48slt"/><path class="zag8i3elj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:watch-wrist-sharp" {...props}></Icon>
<style>
:global(.pfpt48slt) {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zag8i3elj) {
  d: path("M17.5 12h1.75M12 9.25V12l2 1.25");
}

:global(.zspz3p-nz) {
  d: path("M9.25 7.25v-4.5h5.5v4.5m-5.5 9.5v4.5h5.5v-4.5");
}

</style>
