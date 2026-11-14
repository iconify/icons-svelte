<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ehs209b4w"/><path class="tg6kllbvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:warning-deep-water" {...props}></Icon>
<style>
:global(.ehs209b4w) {
  d: path("m12 3l9.5 17.5h-19Z");
}

:global(.tg6kllbvn) {
  d: path("M9.5 12.75q1.25-1.25 2.5 0t2.5 0M7.5 17q1.5-1.25 3 0t3 0t3 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
