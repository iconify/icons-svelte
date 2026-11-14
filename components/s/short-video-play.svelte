<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hwzp73xdl"/><path class="glr0aybio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:short-video-play" {...props}></Icon>
<style>
:global(.glr0aybio) {
  d: path("m12.055 9.967l1.206.768a1.5 1.5 0 0 1 0 2.53l-1.206.768a1.5 1.5 0 0 1-2.305-1.266v-1.534a1.5 1.5 0 0 1 2.305-1.266");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwzp73xdl) {
  d: path("M10.375 2.5h3.25A4.375 4.375 0 0 1 18 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-3.25A4.375 4.375 0 0 1 6 17.125V6.875A4.375 4.375 0 0 1 10.375 2.5");
}

</style>
