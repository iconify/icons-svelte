<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbt7powrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-crop-portrait" {...props}></Icon>
<style>
:global(.zbt7powrw) {
  fill: currentColor;
  d: path("M19 3H5v18h14zm-2 16H7V5h10z");
}

</style>
