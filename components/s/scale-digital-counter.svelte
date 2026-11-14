<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozgz4e58r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:scale-digital-counter" {...props}></Icon>
<style>
:global(.ozgz4e58r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5L4.5 15h15l1.5 5.5Zm1.5-8h15m-7.5-4v4M7 3h10v5.5H7Zm2.5 2.75h5");
}

</style>
