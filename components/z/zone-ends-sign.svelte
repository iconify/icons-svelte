<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n636tb6ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:zone-ends-sign" {...props}></Icon>
<style>
:global(.n636tb6ym) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m4.75 4.75l9.5-9.5M11.5 17.5l6-6m-11 1l6-6");
}

</style>
