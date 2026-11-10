<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbojf1h-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:text-insert-sharp" {...props}></Icon>
<style>
:global(.vbojf1h-d) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 3H22M14 9H22M2 15H22M2 21H22M8.312 2.73L11 5.25L8.284 7.8M11 5.25H3V10");
}

</style>
