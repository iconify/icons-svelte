<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twhymzbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-drag-handle" {...props}></Icon>
<style>
:global(.twhymzbxt) {
  fill: currentColor;
  d: path("M4 9h16v2H4zm0 4h16v2H4z");
}

</style>
