<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfq1fnbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:type-variable-sharp-fill" {...props}></Icon>
<style>
:global(.vfq1fnbxs) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7L6 3L18 3L18 7M12 3L12 11M8 11L16 11M2 18L14 18M22 18L17 18M17 14L17 22");
}

</style>
