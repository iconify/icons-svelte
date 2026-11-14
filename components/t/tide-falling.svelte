<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhg_yxb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tide-falling" {...props}></Icon>
<style>
:global(.hhg_yxb7b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0M3 21.5h18m-9-19V11M8.5 7.5L12 11l3.5-3.5");
}

</style>
