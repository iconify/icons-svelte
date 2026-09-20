<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wnz9a7lxg"/><path class="syzwwuxww"/><path class="k2jzr9u7f"/><path class="uyba0j-4z"/><path class="wuegxr5di"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:subagent-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2jzr9u7f) {
  d: path("M5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.syzwwuxww) {
  fill: currentColor;
  d: path("M13 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uyba0j-4z) {
  d: path("M13 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.wnz9a7lxg) {
  fill: currentColor;
  d: path("M5 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wuegxr5di) {
  d: path("m10 9 4 4");
}

</style>
