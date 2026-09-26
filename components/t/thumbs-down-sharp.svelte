<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnqz1gbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:thumbs-down-sharp" {...props}></Icon>
<style>
:global(.dnqz1gbqh) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 14L16 14L14 22L9 22L8 14L2 14L6.5 2L22 2ZM16 14L16 2");
}

</style>
