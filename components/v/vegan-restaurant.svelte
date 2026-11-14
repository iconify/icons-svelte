<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ebhr9vvxh"/><path class="ka8ma1b1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vegan-restaurant" {...props}></Icon>
<style>
:global(.ebhr9vvxh) {
  d: path("M11.604 20.5H3V10l9-6.5l9 6.5v1.696");
}

:global(.ka8ma1b1v) {
  d: path("M6.5 14H11v6.5H6.5Zm8 7.5c0-4.5 2.5-7 7-7c0 4.5-2.5 7-7 7Zm0 0l4-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
