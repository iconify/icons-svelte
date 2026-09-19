<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwga7cb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-expand" {...props}></Icon>
<style>
:global(.wwga7cb-p) {
  fill: currentColor;
  d: path("M4 20h16v2H4zM4 2h16v2H4zm9 7h3l-4-4l-4 4h3v6H8l4 4l4-4h-3z");
}

</style>
