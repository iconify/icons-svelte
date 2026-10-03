<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvp2jcb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-out-up-right-fill" {...props}></Icon>
<style>
:global(.jvp2jcb3r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 7L6 7C4.3431 7 3 8.3431 3 10L3 18C3 19.6569 4.3431 21 6 21L14 21C15.6569 21 17 19.6569 17 18L17 15M13 11L20.5 3.5M13 3L20.5 3C20.7761 3 21 3.2239 21 3.5L21 11");
}

</style>
