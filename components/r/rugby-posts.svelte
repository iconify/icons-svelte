<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c60xk8rke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rugby-posts" {...props}></Icon>
<style>
:global(.c60xk8rke) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5v19m11-19v19M6.5 13h11m-15 8.5h19");
}

</style>
