<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5804ubjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-eject" {...props}></Icon>
<style>
:global(.w5804ubjm) {
  fill: currentColor;
  d: path("M5 17h14v2H5zm7-12L5.33 15h13.34z");
}

</style>
