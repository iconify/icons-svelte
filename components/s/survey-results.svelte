<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h97wufbck"/><path class="mjlqhrnwk"/><path class="lqlek_mqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:survey-results" {...props}></Icon>
<style>
:global(.h97wufbck) {
  d: path("M2.5 3H7v4.5H2.5Zm0 6.75H7v4.5H2.5Zm0 6.75H7V21H2.5Z");
}

:global(.lqlek_mqf) {
  fill: currentColor;
  d: path("M9.5 4h12v2.5h-12Zm0 6.75h7v2.5h-7Zm0 6.75H19V20H9.5Z");
}

:global(.mjlqhrnwk) {
  d: path("M3.75 5.25L4.5 6l1.25-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
