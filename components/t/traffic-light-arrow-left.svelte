<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sn53yvl9w"/><path class="gw__ijwvb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:traffic-light-arrow-left" {...props}></Icon>
<style>
:global(.gw__ijwvb) {
  d: path("m11 14.5l-2 2l2 2");
}

:global(.sn53yvl9w) {
  d: path("M7.5 2h9v20h-9ZM12 6h.01M12 10h.01M15 16.5H9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
