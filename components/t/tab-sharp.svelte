<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5mnlg7fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tab-sharp" {...props}></Icon>
<style>
:global(.h5mnlg7fd) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm10-9h7V6h-7z");
}

</style>
