<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz2820bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sort-descending" {...props}></Icon>
<style>
:global(.lz2820bcw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.5h9m-9 5.5h6.5m-6.5 5.5h4m9.5-12.75v14.5m-3.5-3.5l3.5 3.5l3.5-3.5");
}

</style>
