<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w7kgzjbrv"/><rect class="espnbvbqq"/><path class="sz57t6b-v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:vertical-align-top" {...props}></Icon>
<style>
:global(.espnbvbqq) {
  width: 5px;
  height: 8.25px;
  x: 13.75px;
  y: 7.25px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sz57t6b-v) {
  d: path("M2.75 3.75h18.5");
}

:global(.w7kgzjbrv) {
  width: 5px;
  height: 13px;
  x: 5.25px;
  y: 7.25px;
  rx: 1.5px;
}

</style>
