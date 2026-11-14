<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xpzx1ob1g"/><path class="kv1vui0zp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ski-patrol" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kv1vui0zp) {
  d: path("M15.621 14.121L7.5 6Q5.5 4 3 4m15.25 11v6.5M15 18.25h6.5");
}

:global(.xpzx1ob1g) {
  d: path("m3.5 19l13-13q2-2 4.5-2");
}

</style>
