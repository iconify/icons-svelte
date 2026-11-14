<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hea6d0bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:transitional-housing" {...props}></Icon>
<style>
:global(.hea6d0bmn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.244 20.5H3.5v-10L12 3.25l8.5 7.25v2.856M15 18h6.25m-2.75-2.75L21.25 18l-2.75 2.75");
}

</style>
