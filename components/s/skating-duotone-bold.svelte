<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f2srn7b1n"/><path class="d4v3t3bns"/><path class="i0a2sm0mq"/><path class="w_zg9ublq"/><path class="uy5j3ks5u"/><path class="ok9ioqb8x"/><path class="pl-e7wb3s"/><path class="zuzyjabxh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:skating-duotone-bold" {...props}></Icon>
<style>
:global(.d4v3t3bns) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f2srn7b1n) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 4v10h12v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i0a2sm0mq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

:global(.pl-e7wb3s) {
  d: path("M6 14v3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uy5j3ks5u) {
  d: path("M6 4v10h12v-3");
}

:global(.w_zg9ublq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 14v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zuzyjabxh) {
  d: path("M18 14v3");
}

</style>
