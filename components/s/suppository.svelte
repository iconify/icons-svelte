<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0oia-hgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:suppository" {...props}></Icon>
<style>
:global(.o0oia-hgf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 16L11 8c3.25-3 6-3.75 7.25-2.25C19.75 7 19 9.75 16 13l-8 7.75Zm2-2.25l5 5");
}

</style>
