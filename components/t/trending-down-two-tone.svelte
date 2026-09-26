<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrix8ccrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:trending-down-two-tone" {...props}></Icon>
<style>
:global(.hrix8ccrj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 7L8.5 13.5L13.5 8.5L21.4 16.4M16 17H21.5C21.7761 17 22 16.7761 22 16.5V11");
}

</style>
