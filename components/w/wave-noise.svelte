<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1nzmubfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wave-noise" {...props}></Icon>
<style>
:global(.r1nzmubfa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11L5 6l2.5 10L10 4l2.5 10.5l2.5-8L17.5 17L20 8l1.5 3m-19 9.5h19");
}

</style>
