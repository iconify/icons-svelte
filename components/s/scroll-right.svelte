<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vvif_vmck"/><path class="z_w_9z0nn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:scroll-right" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vvif_vmck) {
  d: path("M4 7.5v-2a2.5 2.5 0 0 1 5 0V21h8.5a2 2 0 0 0 2-2V3h-13M4 7.5h5m2.75 4.5h5");
}

:global(.z_w_9z0nn) {
  d: path("m14.25 9.5l2.5 2.5l-2.5 2.5");
}

</style>
