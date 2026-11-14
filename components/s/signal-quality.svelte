<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj5s5ysgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:signal-quality" {...props}></Icon>
<style>
:global(.zj5s5ysgx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11C4.25 4.25 7.5 4.25 9 11s4.75 6.75 6.25 0S20 4.25 21.5 11m-6.75 7l2 2L21 15.75");
}

</style>
