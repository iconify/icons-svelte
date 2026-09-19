<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gii-66bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-view-comfy" {...props}></Icon>
<style>
:global(.gii-66bpc) {
  fill: currentColor;
  d: path("M2 4v7h20V4zm8 16h12v-7H10zm-8 0h6v-7H2z");
}

</style>
