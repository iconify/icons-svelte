<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk-mwpqsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-snippet-sharp" {...props}></Icon>
<style>
:global(.qk-mwpqsh) {
  fill: currentColor;
  d: path("M3 21V3h12l6 6v12zm4-4h10v-2H7zm0-4h10v-2H7zm0-4h7V7H7z");
}

</style>
