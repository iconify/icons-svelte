<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="oecphbwmk"/><circle class="juagu4zdo"/><circle class="rxgp3fbut"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:therefore" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.juagu4zdo) {
  cx: 5.5px;
  cy: 17.75px;
  r: 2.5px;
}

:global(.oecphbwmk) {
  cx: 12px;
  cy: 6px;
  r: 2.5px;
}

:global(.rxgp3fbut) {
  cx: 18.5px;
  cy: 17.75px;
  r: 2.5px;
}

</style>
