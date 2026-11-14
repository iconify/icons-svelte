<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bsrt7iseb"/><path class="v95_yxb5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wild-rose-hip" {...props}></Icon>
<style>
:global(.bsrt7iseb) {
  d: path("M6.5 12.5a5.5 7 0 1 0 11 0a5.5 7 0 1 0-11 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v95_yxb5p) {
  d: path("M12 5.5c0-1.5.75-2.25 2.25-2.5m0 0c1.25 2 3.5 2.75 5.75 2c-1.25-2-3.5-2.75-5.75-2m-5 18.75L12 19.5l2.75 2.25");
}

</style>
