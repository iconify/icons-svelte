<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l3403000v"/><path class="zbf076buh"/><path class="l95cxhb0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:slow-motion-sharp" {...props}></Icon>
<style>
:global(.l3403000v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a9.25 9.25 0 0 1 0 18.5");
}

:global(.l95cxhb0w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.83 9.05l3.59 2.4l.83.55l-.83.55l-3.59 2.4l-.83.55v-7z");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.zbf076buh) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.61 20.93h.01m-4.16-2.39h.01m-2.4-4.15h.01m-.01-4.78h.01m2.38-4.15h.01m4.14-2.39h.01");
}

</style>
