<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="guy77pi4w"/><path class="et3w-obqz"/><path class="frmerx2dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-spatial-audio" {...props}></Icon>
<style>
:global(.et3w-obqz) {
  fill: currentColor;
  d: path("M16.39 15.56C14.71 14.7 12.53 14 10 14s-4.71.7-6.39 1.56A2.97 2.97 0 0 0 2 18.22V21h16v-2.78c0-1.12-.61-2.15-1.61-2.66M16 1h-2a9 9 0 0 0 9 9V8c-3.86 0-7-3.14-7-7");
}

:global(.frmerx2dj) {
  fill: currentColor;
  d: path("M20 1h-2c0 2.76 2.24 5 5 5V4c-1.65 0-3-1.35-3-3");
}

:global(.guy77pi4w) {
  cx: 10px;
  cy: 9px;
  r: 4px;
  fill: currentColor;
}

</style>
