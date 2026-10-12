<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xjot2i5mc"/><path class="umtymsyts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spear-phishing" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.umtymsyts) {
  d: path("M2.75 5.75L12 11.5l9.25-5.75M12 11.5v3.25a2.25 2.25 0 0 1-4.5 0v-1.5");
}

:global(.xjot2i5mc) {
  width: 18.5px;
  height: 16px;
  x: 2.75px;
  y: 4.25px;
  rx: 2px;
}

</style>
