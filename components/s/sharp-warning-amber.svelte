<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnmuwpebc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-warning-amber" {...props}></Icon>
<style>
:global(.tnmuwpebc) {
  fill: currentColor;
  d: path("M12 5.99L19.53 19H4.47zM12 2L1 21h22zm1 14h-2v2h2zm0-6h-2v4h2z");
}

</style>
