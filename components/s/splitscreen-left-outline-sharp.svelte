<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_bqi0bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:splitscreen-left-outline-sharp" {...props}></Icon>
<style>
:global(.d_bqi0bwg) {
  fill: currentColor;
  d: path("M4.615 20V4h6v16zm8.77 0V4h6v16zm5-15h-4v14h4z");
}

</style>
