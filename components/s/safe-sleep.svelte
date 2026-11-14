<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nli8o0e8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:safe-sleep" {...props}></Icon>
<style>
:global(.nli8o0e8f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8v12.5M21 8v12.5M3 11h18M3 17h18M7.5 11v6m4.5-6v6m4.5-6v6m-4-14.5A3 3 0 1 0 15 7a2.25 2.25 0 0 1-2.5-4.5Z");
}

</style>
