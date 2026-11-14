<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-llulbzs"/><path class="bara7tbgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:twisted-pair" {...props}></Icon>
<style>
:global(.bara7tbgf) {
  d: path("M2.5 15C7 15 7 9 12 9s5 6 9.5 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-llulbzs) {
  d: path("M2.5 9C7 9 7 15 12 15s5-6 9.5-6");
}

</style>
