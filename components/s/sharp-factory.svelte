<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8tcqbwjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-factory" {...props}></Icon>
<style>
:global(.g8tcqbwjl) {
  fill: currentColor;
  d: path("M22 10v12H2V10l7-3v2l5-2v3zm-4.8-1.5L18 2h3l.8 6.5zM11 18h2v-4h-2zm-4 0h2v-4H7zm10-4h-2v4h2z");
}

</style>
