<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e68te4bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-array-sharp" {...props}></Icon>
<style>
:global(.e68te4bek) {
  fill: currentColor;
  d: path("M3 19V5h3v14zm4 0V5h10v14zm11 0V5h3v14z");
}

</style>
