<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t8d_9mp8e"/><rect class="ackxhlb9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spike-strip" {...props}></Icon>
<style>
:global(.ackxhlb9k) {
  width: 18.5px;
  height: 4.5px;
  x: 2.75px;
  y: 15px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t8d_9mp8e) {
  d: path("m3.64 14.52l1.32-4.54q.14-.48.28 0l1.32 4.54q.14.48.28 0l1.32-4.54q.14-.48.28 0l1.32 4.54q.14.48.28 0l1.32-4.54q.14-.48.28 0l1.32 4.54q.14.48.28 0l1.32-4.54q.14-.48.28 0l1.32 4.54q.14.48.28 0l1.32-4.54q.14-.48.28 0l1.32 4.54q.14.48-.36.48H4q-.5 0-.36-.48");
}

</style>
