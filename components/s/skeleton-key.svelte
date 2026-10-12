<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="inf4ddb2s"/><path class="o6a500beq"/><path class="m4_8dnm3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:skeleton-key" {...props}></Icon>
<style>
:global(.inf4ddb2s) {
  cx: 12px;
  cy: 6px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m4_8dnm3c) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25V21m-2-8.75h4m-2 5.25H8.5M12 21H8.5");
}

:global(.o6a500beq) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
