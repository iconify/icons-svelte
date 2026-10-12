<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xhp3s_b6r"/><path class="cz5-ttb5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tape-measure" {...props}></Icon>
<style>
:global(.cz5-ttb5g) {
  d: path("M13.75 11.25a3.5 3.5 0 1 1-7 0a3.5 3.5 0 1 1 7 0m4 3h3.5v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xhp3s_b6r) {
  width: 15px;
  height: 15px;
  x: 2.75px;
  y: 3.75px;
  rx: 3.5px;
}

</style>
