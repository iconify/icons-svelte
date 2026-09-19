<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz9n24bpt"/><path class="mxrwm4bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-desk" {...props}></Icon>
<style>
:global(.kz9n24bpt) {
  fill: currentColor;
  d: path("M16 8h4v2h-4zm0 4h4v2h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.mxrwm4bmj) {
  fill: currentColor;
  d: path("M2 6v12h2V8h10v10h2v-2h4v2h2V6zm18 8h-4v-2h4zm0-4h-4V8h4z");
}

</style>
