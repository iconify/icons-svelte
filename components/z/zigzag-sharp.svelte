<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj-t1ib0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:zigzag-sharp" {...props}></Icon>
<style>
:global(.gj-t1ib0v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 10.25l4.5-4.5l4.5 4.5l4.5-4.5l4.5 4.5m-18 8l4.5-4.5l4.5 4.5l4.5-4.5l4.5 4.5");
}

</style>
