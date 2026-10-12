<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="inf4ddb2s"/><path class="o6a500beq"/><path class="r7cu8abou"/><rect class="cer02ou4x"/><path class="wxjdvqbmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:surveyor-pole" {...props}></Icon>
<style>
:global(.cer02ou4x) {
  width: 2.5px;
  height: 9.5px;
  x: 10.75px;
  y: 11.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.inf4ddb2s) {
  cx: 12px;
  cy: 6px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o6a500beq) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6h.01");
}

:global(.r7cu8abou) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25v2.5");
}

:global(.wxjdvqbmi) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 15h2.5m-2.5 3.25h2.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
