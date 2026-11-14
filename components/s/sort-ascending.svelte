<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acxgz3b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sort-ascending" {...props}></Icon>
<style>
:global(.acxgz3b7k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4v16m-3-3l3 3l3-3m3-11h4m-4 6H19m-6.5 6h9");
}

</style>
