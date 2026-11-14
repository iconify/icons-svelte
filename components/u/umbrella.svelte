<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df9i48hvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:umbrella" {...props}></Icon>
<style>
:global(.df9i48hvx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 0 1 19 0Zm9.5 0v6.5a2 2 0 0 1-4 0");
}

</style>
