<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3e9pfbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:volume-minus-sharp" {...props}></Icon>
<style>
:global(.u3e9pfbec) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 9L6 9L11 4.0019L11 19.9981L6 15L2 15L2 9ZM15 12L23 12");
}

</style>
