<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rqlutefrv"/><path class="patdnnb-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shortwave-radio" {...props}></Icon>
<style>
:global(.patdnnb-x) {
  d: path("M5.25 14.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm8.75 0h4.5");
}

:global(.rqlutefrv) {
  d: path("M2.5 8h19v13h-19ZM15 8l5-5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
