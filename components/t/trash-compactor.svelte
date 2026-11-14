<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jfqjlnb_c"/><path class="b4hu1abqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:trash-compactor" {...props}></Icon>
<style>
:global(.b4hu1abqx) {
  d: path("M15.25 18.25L18 21l2.75-2.75");
}

:global(.jfqjlnb_c) {
  d: path("M14.3 21.25H3.5V9.75h15v1.9M5.5 7h11M11 2.5V7m7 7.5V21");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
