<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqxfwibxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-desktop-mac" {...props}></Icon>
<style>
:global(.iqxfwibxg) {
  fill: currentColor;
  d: path("M23 2H1v16h9l-2 3v1h8v-1l-2-3h9zm-2 12H3V4h18z");
}

</style>
