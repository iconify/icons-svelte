<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="geo4orbdh"/><rect class="t1wjljbgx"/><path class="uuibwnbqz"/><rect class="dyp638f-f"/><path class="fb52gvgnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tesla-coil" {...props}></Icon>
<style>
:global(.dyp638f-f) {
  width: 9.5px;
  height: 2.75px;
  x: 7.25px;
  y: 18.5px;
  rx: 1px;
}

:global(.fb52gvgnj) {
  d: path("m5 10l-1.75 2.5h2.5L4 15.25M19 10l1.75 2.5h-2.5L20 15.25");
}

:global(.geo4orbdh) {
  width: 12.5px;
  height: 4.5px;
  x: 5.75px;
  y: 3.25px;
  rx: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t1wjljbgx) {
  width: 5.5px;
  height: 10.75px;
  x: 9.25px;
  y: 7.75px;
  rx: 1px;
}

:global(.uuibwnbqz) {
  d: path("M9.25 11h5.5m-5.5 3.75h5.5");
}

</style>
