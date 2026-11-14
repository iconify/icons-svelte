<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o75_0blti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vibration" {...props}></Icon>
<style>
:global(.o75_0blti) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3h8v18H8ZM4.5 7L3 9.5L4.5 12L3 14.5L4.5 17m15-10L21 9.5L19.5 12l1.5 2.5l-1.5 2.5");
}

</style>
