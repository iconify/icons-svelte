<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyevnvb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:transform" {...props}></Icon>
<style>
:global(.uyevnvb8o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h4v4h-4Zm15 0h4v4h-4Zm-15 15h4v4h-4Zm15 0h4v4h-4Zm-9-13h7m-7 15h7m-11-11v7m15-7v7");
}

</style>
