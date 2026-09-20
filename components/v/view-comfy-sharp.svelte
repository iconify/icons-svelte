<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0vsvgbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-comfy-sharp" {...props}></Icon>
<style>
:global(.o0vsvgbcl) {
  fill: currentColor;
  d: path("M2 11V4h20v7zm8 9v-7h12v7zm-8 0v-7h6v7z");
}

</style>
