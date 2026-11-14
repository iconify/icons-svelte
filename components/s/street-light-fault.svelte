<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kg7uilhnr"/><path class="kfiu4t7ix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:street-light-fault" {...props}></Icon>
<style>
:global(.kfiu4t7ix) {
  d: path("m11 7.5l2-4h6l2 4Zm7 7V18m0 3h.01");
}

:global(.kg7uilhnr) {
  d: path("M3 21h6m-3 0V8.5a5 5 0 0 1 5-5h2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
