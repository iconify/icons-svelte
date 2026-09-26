<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="aujhr3btl"/><path class="xmeb_n1nn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-2-check-sharp-fill" {...props}></Icon>
<style>
:global(.aujhr3btl) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 11C20 15.9706 15.9706 20 11 20C6.0294 20 2 15.9706 2 11C2 6.0294 6.0294 2 11 2C15.9706 2 20 6.0294 20 11ZM7.8672 11.8185L9.8115 13.8184C9.9998 14.012 10.2584 14.1213 10.5285 14.1213C10.8769 14.1213 11.2001 13.94 11.3818 13.6428L14.2669 8.9216L12.5604 7.8787L10.3472 11.5002L9.3012 10.4243L7.8672 11.8185Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xmeb_n1nn) {
  d: path("M16.2929 16.2929L21.2929 21.2929");
}

</style>
