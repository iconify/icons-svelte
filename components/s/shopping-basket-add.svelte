<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erawi2boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shopping-basket-add" {...props}></Icon>
<style>
:global(.erawi2boj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5h19l-.5 2.75h-8.75v8.25H4.5Zm4.5 0l3-6m7 6l-3-6M8 13v4m10-2v6m-3-3h6");
}

</style>
