<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="uaxmdsbmr"/><path class="l5s9-om_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:tipi-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.l5s9-om_d) {
  d: path("M238.74 211.69L137.5 53.5l21.24-33.19a8 8 0 0 0-13.48-8.62L128 38.66l-17.26-27a8 8 0 1 0-13.48 8.62L118.5 53.5L17.26 211.69A8 8 0 0 0 24 224h208a8 8 0 0 0 6.74-12.31M86.3 208l41.7-65.16L169.7 208Zm102.4 0l-54-84.31a8 8 0 0 0-13.48 0L67.3 208H38.62L128 68.34L217.38 208Z");
}

:global(.uaxmdsbmr) {
  d: path("M184.32 216H71.68L128 128Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
