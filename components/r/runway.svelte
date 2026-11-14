<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5jc40brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:runway" {...props}></Icon>
<style>
:global(.u5jc40brn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 21l2-17.5h4L16 21Zm4-15.5v3m0 3v3m0 2.5v2");
}

</style>
