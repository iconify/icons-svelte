<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uy91f4czm"/><path class="hmekf-bdm"/><path class="qfgxpvbvs"/><path class="me177l4bh"/><path class="o5ex3bb1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:type-agent-outline-thin" {...props}></Icon>
<style>
:global(.hmekf-bdm) {
  d: path("M3 15a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.me177l4bh) {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.o5ex3bb1u) {
  d: path("M16 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qfgxpvbvs) {
  d: path("M6 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.uy91f4czm) {
  d: path("M13.69 2.37a4 4 0 1 1 -3.38 0");
}

</style>
