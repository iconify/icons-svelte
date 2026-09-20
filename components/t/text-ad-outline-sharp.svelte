<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayg-oyf_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-ad-outline-sharp" {...props}></Icon>
<style>
:global(.ayg-oyf_t) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V6H4zm0 0V6zm1-1h14v-2H5zm0-4h14v-2H5zm0-4h10V7H5z");
}

</style>
