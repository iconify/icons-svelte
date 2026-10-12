<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7_h-0bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:swap-horizontal-sharp" {...props}></Icon>
<style>
:global(.m7_h-0bmj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.75h15.5m-3.5-3.5l3.5 3.5l-3.5 3.5m3.5 5H4.25m3.5-3.5l-3.5 3.5l3.5 3.5");
}

</style>
