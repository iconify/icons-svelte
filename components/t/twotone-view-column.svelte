<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_nrw8bmo"/><path class="no8cyefhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-view-column" {...props}></Icon>
<style>
:global(.m_nrw8bmo) {
  fill: currentColor;
  d: path("M8.33 17H5V7h3.33zm5.34 0h-3.33V7h3.33zM19 17h-3.33V7H19z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.no8cyefhu) {
  fill: currentColor;
  d: path("M3 5v14h18V5zm5.33 12H5V7h3.33zm5.34 0h-3.33V7h3.33zM19 17h-3.33V7H19z");
}

</style>
