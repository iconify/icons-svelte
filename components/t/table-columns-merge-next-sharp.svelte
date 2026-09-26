<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sirkifb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-columns-merge-next-sharp" {...props}></Icon>
<style>
:global(.sirkifb5g) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L3 21L21 21L21 3L3 3ZM7 3L7 21M16 3L16 6M16 21L16 18M10 12L17 12M13.7071 8.7071L17 12L13.7071 15.2929");
}

</style>
