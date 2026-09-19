<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik3ck5bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-door-front" {...props}></Icon>
<style>
:global(.ik3ck5bam) {
  fill: currentColor;
  d: path("M19 19V3H5v16H3v2h18v-2zm-4-6h-2v-2h2z");
}

</style>
