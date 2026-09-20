<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flu_6jb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:split-scene-outline-sharp" {...props}></Icon>
<style>
:global(.flu_6jb3e) {
  fill: currentColor;
  d: path("M3 20V4h6v2H5v12h4v2zm8 2V2h2v2h8v16h-8v2zm2-4h6V6h-6zm-8 0V6zm14 0V6z");
}

</style>
