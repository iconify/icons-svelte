<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nbg9kmbjr"/><path class="tumq4acuv"/><path class="pofc7ubae"/><path class="l18c8xbrk"/><path class="m4mj7rdxr"/><path class="o96t7tbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shell-agent-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l18c8xbrk) {
  d: path("M8.69 4.37a4 4 0 1 1 -3.38 0");
}

:global(.m4mj7rdxr) {
  d: path("m13 12 3.5 3.5L13 19");
}

:global(.nbg9kmbjr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.69 4.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o96t7tbzh) {
  d: path("M18.5 19h3");
}

:global(.pofc7ubae) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 19h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tumq4acuv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 12 3.5 3.5L13 19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
