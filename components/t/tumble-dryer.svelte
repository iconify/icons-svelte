<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mfk2iexay"/><path class="m4l6qglui"/><path class="r8aju0a9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tumble-dryer" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m4l6qglui) {
  d: path("M7 14a5 5 0 1 0 10 0a5 5 0 1 0-10 0m10-9.5h.01");
}

:global(.mfk2iexay) {
  d: path("M7 2.5h10A3.5 3.5 0 0 1 20.5 6v12a3.5 3.5 0 0 1-3.5 3.5H7A3.5 3.5 0 0 1 3.5 18V6A3.5 3.5 0 0 1 7 2.5m-3.5 4h17");
}

:global(.r8aju0a9p) {
  d: path("M9.5 13q1.25-1 2.5 0t2.5 0m-5 2.5q1.25-1 2.5 0t2.5 0");
}

</style>
