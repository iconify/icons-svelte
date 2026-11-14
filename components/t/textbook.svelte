<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hls0jebpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:textbook" {...props}></Icon>
<style>
:global(.hls0jebpf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 18.5V5a2 2 0 0 1 2-2h12v13.5H7a2 2 0 0 0 0 4h12m-9.5-13h6m-6 3.5h4");
}

</style>
