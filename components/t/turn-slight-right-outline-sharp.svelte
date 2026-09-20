<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx6bj0efx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:turn-slight-right-outline-sharp" {...props}></Icon>
<style>
:global(.wx6bj0efx) {
  fill: currentColor;
  d: path("M9 20v-8.4L14.6 6h-2.25V4H18v5.65h-2V7.4l-5 5V20z");
}

</style>
