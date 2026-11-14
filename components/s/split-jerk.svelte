<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="onhvkmavh"/><path class="jmln-1bln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:split-jerk" {...props}></Icon>
<style>
:global(.jmln-1bln) {
  d: path("M10.25 8.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.onhvkmavh) {
  d: path("M2.5 4h19M4 2v4m16-4v4M6.5 4l2 8.5h7l2-8.5M12 12.5V16m-7.5 5.5l3-4L12 16l7.5 5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
