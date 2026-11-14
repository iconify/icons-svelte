<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hcczkwbhd"/><path class="q6hf1pbkj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spreadsheet-db" {...props}></Icon>
<style>
:global(.hcczkwbhd) {
  d: path("M11.7 15.5H2.5v-13h15v8.2m-15-4.2h15m-7.5 0v9m-7.5-5h15m-3 4.5a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0Z");
}

:global(.q6hf1pbkj) {
  d: path("M14.5 15v5a3.5 1.5 0 0 0 7 0v-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
