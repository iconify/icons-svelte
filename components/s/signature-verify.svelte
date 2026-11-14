<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx3wrnbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:signature-verify" {...props}></Icon>
<style>
:global(.tx3wrnbjj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15c2-6 4-7.5 5-6s-1.5 7 .5 7c1.5 0 2.5-4 4-4c1 0 .5 3 2 3M3 19.5h8.5m3.25-1.5l2 2L21 15.75");
}

</style>
