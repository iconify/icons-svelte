<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on1lewblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-signal-cellular-connected-no-internet-0-bar" {...props}></Icon>
<style>
:global(.on1lewblq) {
  fill: currentColor;
  d: path("M20 18h2v-8h-2zm0 4h2v-2h-2zm-2-2v2H2L22 2v6h-2V6.83L6.83 20z");
}

</style>
