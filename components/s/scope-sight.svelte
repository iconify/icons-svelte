<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhxgrybwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:scope-sight" {...props}></Icon>
<style>
:global(.hhxgrybwp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12a8 8 0 1 0 16 0a8 8 0 1 0-16 0Zm8-9.5V9m0 6v6.5M2.5 12H9m6 0h6.5M12 12h.01");
}

</style>
