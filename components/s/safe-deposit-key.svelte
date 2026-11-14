<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niu_3j0ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:safe-deposit-key" {...props}></Icon>
<style>
:global(.niu_3j0ol) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8 0h9m-3 0v3m3-3v2.5");
}

</style>
