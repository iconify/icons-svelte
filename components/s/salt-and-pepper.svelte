<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydw9x4buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:salt-and-pepper" {...props}></Icon>
<style>
:global(.ydw9x4buk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10h7L10 20H4Zm10 0h7L20 20h-6Zm-10-4.5h7v4h-7Zm10 0h7v4h-7Z");
}

</style>
