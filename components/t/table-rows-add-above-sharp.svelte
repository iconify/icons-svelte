<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwf0mfbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-rows-add-above-sharp" {...props}></Icon>
<style>
:global(.lwf0mfbey) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 4L3 4L3 22L21 22L21 4L18 4M3 13L21 13M12 1L12 9M8 5L16 5");
}

</style>
