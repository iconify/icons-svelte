<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9h3n3hwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wind-sharp" {...props}></Icon>
<style>
:global(.r9h3n3hwf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.75h11A2.75 2.75 0 1 0 11 7m-8.25 6.75h15.5a3 3 0 1 1-3 3m-12.5 1h8.5");
}

</style>
