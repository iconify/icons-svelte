<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0v91cgqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vinegar-cleaner" {...props}></Icon>
<style>
:global(.o0v91cgqo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.3 21.5H3.5V10h10v8.5M6 10V3.5h8.5v3H11V10m-7.5 5h10m2.5 6.5c0-4.75 2.25-6.5 5.75-6.5c0 4-2 6.5-5.75 6.5Zm0 0l2.75-3.25");
}

</style>
