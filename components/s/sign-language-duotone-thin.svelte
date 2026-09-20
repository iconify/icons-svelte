<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6kdjab3n"/><path class="avf-3ybgy"/><path class="yhc-cm80y"/><path class="qnm4x6bjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sign-language-duotone-thin" {...props}></Icon>
<style>
:global(.avf-3ybgy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 21v-8a2 2 0 0 0 -4 0V9a2 2 0 0 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qnm4x6bjh) {
  d: path("M20 21v-8a2 2 0 0 0 -4 0V9a2 2 0 0 0 -4 0");
}

:global(.w6kdjab3n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21v-8a2 2 0 0 1 4 0V9a2 2 0 0 1 4 0v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yhc-cm80y) {
  d: path("M4 21v-8a2 2 0 0 1 4 0V9a2 2 0 0 1 4 0v6");
}

</style>
