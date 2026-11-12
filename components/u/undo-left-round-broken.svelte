<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkkez7bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-left-round-broken" {...props}></Icon>
<style>
:global(.lkkez7bnt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7H15C17.7614 7 20 9.23857 20 12C20 14.7614 17.7614 17 15 17M7 10L4 7L7 4M11 17H8.00001");
}

</style>
