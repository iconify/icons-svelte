<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c75ia47oq"/><path class="s65qukbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-charging-30" {...props}></Icon>
<style>
:global(.c75ia47oq) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v10.5h2L13 7v5.5h2l-1.07 2H17z");
}

:global(.s65qukbuk) {
  fill: currentColor;
  d: path("M11 20v-5.5H7V22h10v-7.5h-3.07z");
}

</style>
