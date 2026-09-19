<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot8b6ybzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-chair-alt" {...props}></Icon>
<style>
:global(.ot8b6ybzx) {
  fill: currentColor;
  d: path("M16 10h3V3H5v7h3v2H5v9h2v-3h10v3h2v-9h-3zM7 8V5h10v3zm10 8H7v-2h10zm-3-4h-4v-2h4z");
}

</style>
