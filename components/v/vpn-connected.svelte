<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r8a9qcmsq"/><path class="c3u4g1nzv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vpn-connected" {...props}></Icon>
<style>
:global(.c3u4g1nzv) {
  d: path("M7.5 10.5a3 7.5 0 1 0 6 0a3 7.5 0 1 0-6 0Zm-4.5 0h15M14.75 18l2 2L21 15.75");
}

:global(.r8a9qcmsq) {
  d: path("M11.154 17.971a7.5 7.5 0 1 1 6.817-6.817");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
