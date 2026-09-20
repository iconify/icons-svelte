<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ra6o68b-z"/><path class="mzjqjtrpb"/><path class="c7p9d-b6q"/><path class="md3qg6xkk"/><path class="pty_wsbvs"/><path class="wvee1b7zr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:type-action-duotone-thin" {...props}></Icon>
<style>
:global(.c7p9d-b6q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.md3qg6xkk) {
  d: path("M4 6v12");
}

:global(.mzjqjtrpb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

:global(.ra6o68b-z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wvee1b7zr) {
  d: path("M8 15h12");
}

</style>
