<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k5mfw8-4w"/><path class="nnvzb1aji"/><path class="skb5wgeiw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:work-from-home" {...props}></Icon>
<style>
:global(.k5mfw8-4w) {
  d: path("M3.5 11.5L12 4l8.5 7.5");
}

:global(.nnvzb1aji) {
  d: path("M5.5 10v10.5h13V10");
}

:global(.skb5wgeiw) {
  d: path("M8.5 13h7v4h-7Zm-1 7.5h9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
