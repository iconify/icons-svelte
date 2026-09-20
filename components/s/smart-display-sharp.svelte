<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7xtcdcqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:smart-display-sharp" {...props}></Icon>
<style>
:global(.s7xtcdcqs) {
  fill: currentColor;
  d: path("M10 15.577L15.577 12L10 8.423zM3 19V5h18v14z");
}

</style>
