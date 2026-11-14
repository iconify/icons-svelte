<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxy2arbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:skew-left" {...props}></Icon>
<style>
:global(.lxy2arbog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5C7 20.5 9 18 11 13c2-5.5 4-7.5 6-7.5s3 8.5 4.5 15");
}

</style>
