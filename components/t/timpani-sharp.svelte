<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb9h2bc7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:timpani-sharp" {...props}></Icon>
<style>
:global(.wb9h2bc7b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h18.5c0 4.5-4.15 8.25-9.25 8.25s-9.25-3.75-9.25-8.25Zm.71 3.2h17.08M7.5 12.94l-2 8.31m11-8.31l2 8.31");
}

</style>
