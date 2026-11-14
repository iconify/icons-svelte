<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fwyyj9yok"/><path class="y0_7bcb8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:treasury-multi-entity" {...props}></Icon>
<style>
:global(.fwyyj9yok) {
  d: path("M8 2.5h8v5H8Zm-5.5 12H7V20H2.5Zm7.25 0h4.5V20h-4.5Zm7.25 0h4.5V20H17Zm-5-7v7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y0_7bcb8m) {
  d: path("M4.75 14.5V11h14.5v3.5");
}

</style>
