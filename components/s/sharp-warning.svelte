<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zamwb1b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-warning" {...props}></Icon>
<style>
:global(.zamwb1b7d) {
  fill: currentColor;
  d: path("M1 21h22L12 2zm12-3h-2v-2h2zm0-4h-2v-4h2z");
}

</style>
