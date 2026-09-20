<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mpxubccrr"/><path class="o35gkxngb"/><path class="pf60eubcf"/><path class="mzs9lvbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stuck-agent-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mpxubccrr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.32 7a5.5 5.5 0 1 1 -4.64 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mzs9lvbbs) {
  d: path("M19.5 4v16");
}

:global(.o35gkxngb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19.5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pf60eubcf) {
  d: path("M11.32 7a5.5 5.5 0 1 1 -4.64 0");
}

</style>
