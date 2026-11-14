<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgo_5pusu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:violet" {...props}></Icon>
<style>
:global(.rgo_5pusu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.25a3.75 3.75 0 1 1 2.75 2a3.75 3.75 0 1 1-1 3.5a3.75 3.75 0 1 1-3.5 0a3.75 3.75 0 1 1-1-3.5a3.75 3.75 0 1 1 2.75-2Zm0 3h.01");
}

</style>
