<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4yogew1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:thumbtack" {...props}></Icon>
<style>
:global(.s4yogew1m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.5h8l-1 7l3 3H6l3-3Zm4 10v8");
}

</style>
