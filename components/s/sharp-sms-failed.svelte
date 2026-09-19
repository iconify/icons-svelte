<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ju72-ipxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-sms-failed" {...props}></Icon>
<style>
:global(.ju72-ipxf) {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h16zm-9 12h-2v-2h2zm0-4h-2V6h2z");
}

</style>
