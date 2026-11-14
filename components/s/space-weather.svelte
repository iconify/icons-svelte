<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-tty3b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:space-weather" {...props}></Icon>
<style>
:global(.k-tty3b_q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7 4.5v-2M4.5 7h-2m2.75-1.75l-1.5-1.5M11 11q2.5-.5 2 2t2 2");
}

</style>
