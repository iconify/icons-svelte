<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chfyeglyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:terminal" {...props}></Icon>
<style>
:global(.chfyeglyq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6.5L10 12l-5.5 5.5m7.5.5h7.5");
}

</style>
