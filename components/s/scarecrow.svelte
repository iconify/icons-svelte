<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cx6qiacja"/><circle class="xr52llboc"/><path class="wvk1jzb1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:scarecrow" {...props}></Icon>
<style>
:global(.cx6qiacja) {
  d: path("M7.75 5.25h8.5m-6.25 0l.5-2.5h3l.5 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wvk1jzb1r) {
  d: path("M2.75 14.5h18.5m-11.95 0h5.4q.8 0 .71.8l-.32 2.9q-.09.8-.89.8H9.8q-.8 0-.89-.8l-.32-2.9q-.09-.8.71-.8M12 19v2.25");
}

:global(.xr52llboc) {
  cx: 12px;
  cy: 9.75px;
  r: 1.75px;
}

</style>
