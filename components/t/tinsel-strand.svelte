<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh1qtqbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tinsel-strand" {...props}></Icon>
<style>
:global(.bh1qtqbag) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8L4 13l1.5-3.5l1.5 5L8.75 11l1.5 4.75L12 12l1.75 3.75l1.5-4.75L17 14.5l1.5-5L20 13l1.5-5");
}

</style>
