<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="evew35b2m"/><circle class="pfpt48slt"/><path class="zag8i3elj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:watch-wrist" {...props}></Icon>
<style>
:global(.evew35b2m) {
  d: path("M9.25 7.25v-3.5a1 1 0 0 1 1-1h3.5a1 1 0 0 1 1 1v3.5m-5.5 9.5v3.5a1 1 0 0 0 1 1h3.5a1 1 0 0 0 1-1v-3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pfpt48slt) {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
}

:global(.zag8i3elj) {
  d: path("M17.5 12h1.75M12 9.25V12l2 1.25");
}

</style>
