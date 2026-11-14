<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8rskvbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:tattoo-machine" {...props}></Icon>
<style>
:global(.b8rskvbzk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 3h5.75A2.625 2.625 0 0 1 14 5.625v.75A2.625 2.625 0 0 1 11.375 9h-5.75A2.625 2.625 0 0 1 3 6.375v-.75A2.625 2.625 0 0 1 5.625 3M11 9l5 8h3l-5-8M8.5 3v6m9 8l2.25 3.75");
}

</style>
