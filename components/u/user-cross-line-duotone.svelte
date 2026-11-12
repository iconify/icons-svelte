<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ip5zz346n"/><circle class="dtl23o_xq"/><path class="nwtni8bmv"/><path class="r0p-ejt9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-cross-line-duotone" {...props}></Icon>
<style>
:global(.dtl23o_xq) {
  cx: 12px;
  cy: 6px;
  r: 4px;
}

:global(.ip5zz346n) {
  d: path("M15.02 13.3317C14.0882 13.1178 13.0685 13 12 13C7.58172 13 4 15.0147 4 17.5C4 19.9853 4 22 12 22C17.5794 22 19.2676 21.02 19.7784 19.5839");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nwtni8bmv) {
  stroke-linejoin: round;
  d: path("M16.666 14.6667L17.9995 16.0002M17.9995 16.0002L19.3327 17.3333M17.9995 16.0002L19.333 14.6667M17.9995 16.0002L16.6663 17.3333");
}

:global(.r0p-ejt9x) {
  d: path("M22 16C22 18.2091 20.2091 20 18 20C15.7909 20 14 18.2091 14 16C14 13.7909 15.7909 12 18 12C20.2091 12 22 13.7909 22 16Z");
}

</style>
