<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vmoc8qbmx"/><path class="ibbr2_bui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:video-intercom" {...props}></Icon>
<style>
:global(.ibbr2_bui) {
  d: path("M13.75 6.5h4.5V11h-4.5Zm.5 9a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vmoc8qbmx) {
  d: path("M2.5 21.5v-18H8v18m3-18h10V20H11Z");
}

</style>
