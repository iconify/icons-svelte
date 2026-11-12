<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2zmq5bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:undo-right-round-broken" {...props}></Icon>
<style>
:global(.b2zmq5bbp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20 7H9C6.23857 7 4 9.23857 3.99999 12C3.99999 14.7614 6.23857 17 8.99999 17M17 10L20 7L17 4M13 17H16");
}

</style>
