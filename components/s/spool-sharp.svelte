<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bivy5sb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:spool-sharp" {...props}></Icon>
<style>
:global(.bivy5sb_w) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 2L20 2L20 6L4 6ZM4 18L20 18L20 22L4 22ZM7 6L7 18M17 6L17 18M7 13.5L17 10.5");
}

</style>
