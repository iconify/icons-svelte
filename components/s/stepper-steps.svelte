<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hajk_sbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:stepper-steps" {...props}></Icon>
<style>
:global(.hajk_sbpv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.75 0h4.5m2.75 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
