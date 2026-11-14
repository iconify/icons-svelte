<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfx_lvb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tree-row" {...props}></Icon>
<style>
:global(.dfx_lvb0k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 17.5l2.25-14L7 17.5Zm7.25 0L12 3.5l2.25 14Zm7.25 0l2.25-14l2.25 14ZM2.5 21h19");
}

</style>
