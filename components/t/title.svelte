<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqz0xrkdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:title" {...props}></Icon>
<style>
:global(.tqz0xrkdc) {
  fill: currentColor;
  d: path("M10.5 20V7H5V4h14v3h-5.5v13z");
}

</style>
