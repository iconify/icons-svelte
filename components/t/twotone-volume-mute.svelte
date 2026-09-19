<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnksk_30m"/><path class="wmoih8eht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-volume-mute" {...props}></Icon>
<style>
:global(.wmoih8eht) {
  fill: currentColor;
  d: path("M7 9v6h4l5 5V4l-5 5zm7-.17v6.34L11.83 13H9v-2h2.83z");
}

:global(.xnksk_30m) {
  fill: currentColor;
  d: path("M9 13h2.83L14 15.17V8.83L11.83 11H9z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
