<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjyg6ea4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:temperature-gauge-device" {...props}></Icon>
<style>
:global(.jjyg6ea4g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 14V5.5a2.5 2.5 0 0 1 5 0V14a4.25 4.25 0 1 1-5 0M12 8v8");
}

</style>
