<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d-y-mqg9z"/><path class="bksmtb6ys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vending-kiosk" {...props}></Icon>
<style>
:global(.bksmtb6ys) {
  d: path("M7.25 4.75h6a1.5 1.5 0 0 1 1.5 1.5v9.5a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5v-9.5a1.5 1.5 0 0 1 1.5-1.5m3 0v12.5m-4.5-8.5h9m-9 4.25h9m3-6.5h.01M16.75 10h2M6.5 19.5H14");
}

:global(.d-y-mqg9z) {
  d: path("M6.125 2.5h11.75A2.625 2.625 0 0 1 20.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 18.875V5.125A2.625 2.625 0 0 1 6.125 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
