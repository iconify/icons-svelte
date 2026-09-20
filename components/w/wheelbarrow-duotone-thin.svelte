<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8jvazqdv"/><path class="o4zw09imi"/><path class="r6xi4ylro"/><path class="lw912obya"/><path class="vm55gtbfg"/><path class="xslwtfbwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wheelbarrow-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lw912obya) {
  d: path("m18 9 3 3");
}

:global(.o4zw09imi) {
  fill: currentColor;
  d: path("M4 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.p8jvazqdv) {
  fill: currentColor;
  d: path("M4 8h14l-3 3H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r6xi4ylro) {
  d: path("M4 8h14l-3 3H7Z");
}

:global(.vm55gtbfg) {
  d: path("M4 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.xslwtfbwz) {
  d: path("M15 11v6");
}

</style>
