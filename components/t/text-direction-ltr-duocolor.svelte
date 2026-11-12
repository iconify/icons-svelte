<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jvykynp5y"/><path class="vy3fg0adm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-direction-ltr-duocolor" {...props}></Icon>
<style>
:global(.jvykynp5y) {
  stroke-opacity: 0.4;
  d: path("m18 21l3-3l-3-3m3 3H3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vy3fg0adm) {
  d: path("M11 3h6m-5 0v8m4-8v8m-5-8a3 3 0 0 0 0 6h1");
}

</style>
