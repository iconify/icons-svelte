<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="i_szjxb6h"/><path class="m9me6bb5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sextant" {...props}></Icon>
<style>
:global(.i_szjxb6h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5L3.25 18.66a17.5 17.5 0 0 0 17.5 0Zm0 6l2.25 6");
}

:global(.m9me6bb5j) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.5h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
