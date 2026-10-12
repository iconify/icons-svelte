<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="enlocj-pa"/><path class="f6_zd5bng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:time-rewind" {...props}></Icon>
<style>
:global(.enlocj-pa) {
  d: path("M12 21.25A9.25 9.25 0 1 0 2.75 12");
}

:global(.f6_zd5bng) {
  d: path("M12 7.25V12l3 2m-9 1.5l-2 2l2 2m3.5-4l-2 2l2 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
