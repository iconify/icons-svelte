<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn0f9jbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wicketkeeper" {...props}></Icon>
<style>
:global(.sn0f9jbhv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M2.5 21c0-4 2.25-6.75 5-6.75s5 2.75 5 6.75m3 0V6.5h6V21m-3-14.5V21");
}

</style>
