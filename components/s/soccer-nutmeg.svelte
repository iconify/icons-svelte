<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pvsc9nbiu"/><path class="giw2gpahb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:soccer-nutmeg" {...props}></Icon>
<style>
:global(.giw2gpahb) {
  d: path("m12 15.25l1.75 1.25l-.75 2h-2l-.75-2Z");
}

:global(.pvsc9nbiu) {
  d: path("m9.75 2.5l-6 18H2m12.25-18l6 18H22M8 17a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
