<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zli7lqbau"/><path class="fwhv0hbce"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:shots-on-target" {...props}></Icon>
<style>
:global(.fwhv0hbce) {
  d: path("M13.25 10.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-6.75 8l5-5m-3.5 0h3.5V17");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zli7lqbau) {
  d: path("M3 20V7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v13");
}

</style>
