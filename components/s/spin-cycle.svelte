<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tgx030-6f"/><path class="dk3zl2b7m"/><path class="bpgy4bnoy"/><path class="t6tiwebme"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spin-cycle" {...props}></Icon>
<style>
:global(.bpgy4bnoy) {
  d: path("M12 9.75A3.25 3.25 0 1 1 8.75 13");
}

:global(.dk3zl2b7m) {
  d: path("M5.5 13a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

:global(.t6tiwebme) {
  d: path("M7.5 14.25L8.75 13L10 14.25");
}

:global(.tgx030-6f) {
  d: path("M3 2.5h18v19H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
