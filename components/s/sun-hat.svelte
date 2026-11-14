<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="akvfs44ao"/><path class="fjsxucbjo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sun-hat" {...props}></Icon>
<style>
:global(.akvfs44ao) {
  d: path("M6 12c0-5 2.5-7 6-7s6 2 6 7Z");
}

:global(.fjsxucbjo) {
  d: path("M2.5 13a9.5 3 0 1 0 19 0a9.5 3 0 1 0-19 0M6 10h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
