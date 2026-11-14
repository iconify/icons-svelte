<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zw58uonmq"/><path class="c7x-jdbji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wall-street-light" {...props}></Icon>
<style>
:global(.c7x-jdbji) {
  d: path("M12.33 8.5h1.34a1.5 1.5 0 0 1 1.471 1.794l-.4 2A1.5 1.5 0 0 1 13.27 13.5h-.54a1.5 1.5 0 0 1-1.471-1.206l-.4-2A1.5 1.5 0 0 1 12.33 8.5m.67 8V19m-3.25-3L8.5 18m7.75-2l1.25 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zw58uonmq) {
  d: path("M3 2.5v19M3 6h10v2.5m-10 2L7.5 6");
}

</style>
