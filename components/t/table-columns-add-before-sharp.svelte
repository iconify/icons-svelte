<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbdv3meof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-columns-add-before-sharp" {...props}></Icon>
<style>
:global(.pbdv3meof) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 18L4 21L22 21L22 3L4 3L4 6M13 21L13 3M5 8L5 16M1 12L9 12");
}

</style>
