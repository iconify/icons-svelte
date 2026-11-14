<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqzmylbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:soccer-stud-key" {...props}></Icon>
<style>
:global(.jqzmylbsh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h10M8 4v11m-1.5 0h3l1.5 2.5L9.5 20h-3L5 17.5Zm8-2h6L19 17h-3Zm3 4v3.5");
}

</style>
