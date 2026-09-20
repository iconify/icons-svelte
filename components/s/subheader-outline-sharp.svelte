<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm16020hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:subheader-outline-sharp" {...props}></Icon>
<style>
:global(.fm16020hs) {
  fill: currentColor;
  d: path("M6.616 9.192h8v-2h-8zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
