<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr9du6qey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:unicycle-sharp" {...props}></Icon>
<style>
:global(.wr9du6qey) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 2.75h6.5v3.5H8v-3.5zM12 6.25V16.5m-1.5-2.25l3 4.5m-1.5-7a4.75 4.75 0 1 0 0 9.5a4.75 4.75 0 0 0 0-9.5Z");
}

</style>
