<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="y8_742q_b"/><path class="yl5a8dzza"/><path class="ij6kxnaih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:row-houses" {...props}></Icon>
<style>
:global(.ij6kxnaih) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 21.25v-3.5h1.5v3.5");
}

:global(.y8_742q_b) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.65V10.6q0-.6.38-1.06l2.32-2.83q.38-.46.76 0l2.33 2.83q.38.46.76 0l2.32-2.83q.38-.46.76 0l2.32 2.83q.38.46.76 0l2.33-2.83q.38-.46.76 0l2.32 2.83q.38.46.38 1.06v10.05q0 .6-.6.6H3.35q-.6 0-.6-.6M8.92 10v11.25M15.08 10v11.25");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.yl5a8dzza) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.83 13.5h.01m6.16-1h.01m6.16 1h.01");
}

</style>
