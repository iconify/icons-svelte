<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vzmnvky3g"/><path class="bfwiu2w4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:undo" {...props}></Icon>
<style>
:global(.bfwiu2w4e) {
  d: path("m8.5 5.5l-4 4l4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vzmnvky3g) {
  d: path("M4.5 9.5h10a5 5 0 0 1 0 10H9");
}

</style>
