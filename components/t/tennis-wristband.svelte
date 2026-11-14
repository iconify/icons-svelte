<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="spjyovp4g"/><path class="emx5mackx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tennis-wristband" {...props}></Icon>
<style>
:global(.emx5mackx) {
  d: path("M3 11.5q9 3 18 0");
}

:global(.spjyovp4g) {
  d: path("M3 7q9 3 18 0v9q-9 3-18 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
