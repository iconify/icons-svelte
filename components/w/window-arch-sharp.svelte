<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr3sohbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:window-arch-sharp" {...props}></Icon>
<style>
:global(.lr3sohbyy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 18V9a6.25 6.25 0 0 1 12.5 0v9ZM12 2.75V18m-6.25-7.5h12.5M3.75 21.25h16.5");
}

</style>
