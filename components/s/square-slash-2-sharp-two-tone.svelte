<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aalcw1b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-slash-2-sharp-two-tone" {...props}></Icon>
<style>
:global(.aalcw1b9r) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4L20 4L20 20L4 20ZM2.7071 21.2929L21.2929 2.7071");
}

</style>
