<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_hxwsbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-hourglass-top" {...props}></Icon>
<style>
:global(.u_hxwsbht) {
  fill: currentColor;
  d: path("m6 2l.01 6L10 12l-3.99 4.01L6 22h12v-6l-4-4l4-3.99V2zm10 14.5V20H8v-3.5l4-4z");
}

</style>
