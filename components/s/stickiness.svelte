<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xj_6ybcze"/><path class="y8o6kfbpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stickiness" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xj_6ybcze) {
  d: path("M12.872 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.544 0 1.065.048m5.929 3.349q.114.22.203.453M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.y8o6kfbpa) {
  d: path("M15 14.5v3.75a3 3 0 0 0 6 0V14.5m-6.75 1.75h1.5m4.5 0h1.5");
}

</style>
