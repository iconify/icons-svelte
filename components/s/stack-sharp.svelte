<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvg529bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stack-sharp" {...props}></Icon>
<style>
:global(.bvg529bcs) {
  fill: currentColor;
  d: path("M6.616 14v1H3V3h12v3.616h-1V4H4v10zM9 21V9h12v12z");
}

</style>
