<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw5vu58kl"/><path class="qukdhgbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-not-equal" {...props}></Icon>
<style>
:global(.qukdhgbip) {
  fill: currentColor;
  d: path("m14.08 4.605l1.84.79l-6 14l-1.84-.79z");
}

:global(.uw5vu58kl) {
  fill: currentColor;
  d: path("M19 9.998H5v-2h14zm0 6H5v-2h14z");
}

</style>
