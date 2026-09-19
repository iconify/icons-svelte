<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hllc59b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-bookmark" {...props}></Icon>
<style>
:global(.hllc59b3d) {
  fill: currentColor;
  d: path("M19 3H5v18l7-3l7 3z");
}

</style>
