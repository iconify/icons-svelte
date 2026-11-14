<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmr_a4-cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:windmill-traditional" {...props}></Icon>
<style>
:global(.zmr_a4-cr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9 21l1.5-10h3L15 21Zm3-10L5 4m7 7l7-7m-7 7l-7 7m7-7l7 7");
}

</style>
