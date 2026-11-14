<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkfmn0g3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tennis-racket" {...props}></Icon>
<style>
:global(.fkfmn0g3b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm1.75 4.25L4 20M17.75 8.75l-4 4m1.5-6.5l-4 4");
}

</style>
