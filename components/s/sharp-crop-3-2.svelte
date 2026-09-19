<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw_eh8bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-crop-3-2" {...props}></Icon>
<style>
:global(.mw_eh8bqc) {
  fill: currentColor;
  d: path("M21 6H3v12h18zm-2 10H5V8h14z");
}

</style>
