<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6sbt-man"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:smart-jump-rope" {...props}></Icon>
<style>
:global(.f6sbt-man) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5zA1.75 1.75 0 0 1 6.5 4.25v4A1.75 1.75 0 0 1 4.75 10A1.75 1.75 0 0 1 3 8.25v-4A1.75 1.75 0 0 1 4.75 2.5m8 0za1.75 1.75 0 0 1 1.75 1.75v4A1.75 1.75 0 0 1 12.75 10A1.75 1.75 0 0 1 11 8.25v-4a1.75 1.75 0 0 1 1.75-1.75m-8 7.5c0 11.5 8 11.5 8 0m3.75 6.5l4.25 3L18.5 21v-6.5l2.25 1.5l-4.25 3");
}

</style>
