<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwxaurmqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:screw" {...props}></Icon>
<style>
:global(.uwxaurmqq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3h11L14 6.5h-4ZM10 6.5h4V16l-2 4.5l-2-4.5Zm0 3.5l4-1m-4 4.5l4-1");
}

</style>
