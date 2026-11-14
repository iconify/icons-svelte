<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdvrbi9pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spine" {...props}></Icon>
<style>
:global(.zdvrbi9pm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5h7v2.75h-7Zm0 5.5h7v2.75h-7Zm0 5.5h7v2.75h-7Zm0 5.5h7v2.75h-7Z");
}

</style>
