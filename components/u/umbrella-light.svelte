<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sdpeuyz2h"/><rect class="huymlt17p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:umbrella-light" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.huymlt17p) {
  width: 5px;
  height: 3.75px;
  x: 9.5px;
  y: 14.25px;
  rx: 1px;
}

:global(.sdpeuyz2h) {
  d: path("M2.75 10.5a9.25 7.75 0 0 1 18.5 0a.75.75 0 0 1-.75.75h-17a.75.75 0 0 1-.75-.75M12 2.75v8.5M7.5 3.9l1.25 7.35M16.5 3.9l-1.25 7.35m-3.25 0v3M12 18v3.25");
}

</style>
