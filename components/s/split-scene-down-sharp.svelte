<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccb2iyuxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:split-scene-down-sharp" {...props}></Icon>
<style>
:global(.ccb2iyuxs) {
  fill: currentColor;
  d: path("M5 9.116V4h14v5.116zM5 20v-7.5H3v-1h18v1h-2V20z");
}

</style>
