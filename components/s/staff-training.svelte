<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t25oj4bxw"/><path class="evw6m15eg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:staff-training" {...props}></Icon>
<style>
:global(.evw6m15eg) {
  d: path("M7 11.75V16c1.25 1.25 3 2 5 2s3.75-.75 5-2v-4.25m3.5-2.25V15");
}

:global(.t25oj4bxw) {
  d: path("m3.5 9.5l8.5-4l8.5 4l-8.5 4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
