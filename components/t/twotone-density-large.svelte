<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjqp-tjxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-density-large" {...props}></Icon>
<style>
:global(.fjqp-tjxv) {
  fill: currentColor;
  d: path("M3 3h18v2H3zm0 16h18v2H3z");
}

</style>
