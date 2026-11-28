<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcrh3-xhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:vector-corner-sharp" {...props}></Icon>
<style>
:global(.qcrh3-xhh) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 5L14 5L14 9L10 9ZM10 8L1.8126 19.4172M14 8L22.1874 19.4172");
}

</style>
