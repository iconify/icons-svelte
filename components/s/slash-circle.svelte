<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl8df7bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:slash-circle" {...props}></Icon>
<style>
:global(.kl8df7bkw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m-1 7.5l15-15");
}

</style>
