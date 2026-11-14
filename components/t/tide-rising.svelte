<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc2c6nbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tide-rising" {...props}></Icon>
<style>
:global(.oc2c6nbbd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0M3 21.5h18M12 11V2.5M8.5 6L12 2.5L15.5 6");
}

</style>
