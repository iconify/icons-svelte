<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqj_6vbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-checklist" {...props}></Icon>
<style>
:global(.zqj_6vbvv) {
  fill: currentColor;
  d: path("M22 7h-9v2h9zm0 8h-9v2h9zM5.54 11L2 7.46l1.41-1.41l2.12 2.12l4.24-4.24l1.41 1.41zm0 8L2 15.46l1.41-1.41l2.12 2.12l4.24-4.24l1.41 1.41z");
}

</style>
