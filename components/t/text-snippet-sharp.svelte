<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k08jmb_yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:text-snippet-sharp" {...props}></Icon>
<style>
:global(.k08jmb_yn) {
  fill: currentColor;
  d: path("M4 20V4h10.789L20 9.211V20zm3.5-4h9v-1h-9zm0-3.5h9v-1h-9zm0-3.5h5.73V8H7.5z");
}

</style>
