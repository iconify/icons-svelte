<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlppqh1ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:severity-critical" {...props}></Icon>
<style>
:global(.mlppqh1ev) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 20v-5m4.5 5v-9m4.5 9V7M19 20V3");
}

</style>
