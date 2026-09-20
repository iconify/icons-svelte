<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsia2hbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-ad-sharp" {...props}></Icon>
<style>
:global(.fsia2hbyl) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm3-3h14v-2H5zm0-4h14v-2H5zm0-4h10V7H5z");
}

</style>
