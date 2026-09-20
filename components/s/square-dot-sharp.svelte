<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_glu1bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:square-dot-sharp" {...props}></Icon>
<style>
:global(.m_glu1bsz) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5H5zm7-3q-1.65 0-2.825-1.175T8 12t1.175-2.825T12 8t2.825 1.175T16 12t-1.175 2.825T12 16");
}

</style>
