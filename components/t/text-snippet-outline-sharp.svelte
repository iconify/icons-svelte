<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0nigdm3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-snippet-outline-sharp" {...props}></Icon>
<style>
:global(.w0nigdm3h) {
  fill: currentColor;
  d: path("M5 19h14V9.825L14.175 5H5zm-2 2V3h12l6 6v12zm4-4h10v-2H7zm0-4h10v-2H7zm0-4h7V7H7zM5 19V5z");
}

</style>
