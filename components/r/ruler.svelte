<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm974abyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ruler" {...props}></Icon>
<style>
:global(.lm974abyu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 9l5-5a1.414 1.414 0 0 1 2 0l4 4a1.414 1.414 0 0 1 0 2L10 20a1.414 1.414 0 0 1-2 0l-4-4a1.414 1.414 0 0 1 0-2zm-4 4l2 2m2-6l2 2m2-6l2 2");
}

</style>
