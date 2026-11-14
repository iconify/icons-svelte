<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbm8hb9be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rugby-penalty-kick" {...props}></Icon>
<style>
:global(.tbm8hb9be) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21a7 7 0 0 1 8-8a7 7 0 0 1-8 8ZM14 2.5V13m7-10.5V13m-7-4.5h7M6.25 17.75l1.5-1.5");
}

</style>
