<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvc_kgbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-vertical-shades" {...props}></Icon>
<style>
:global(.yvc_kgbsu) {
  fill: currentColor;
  d: path("M20 19V3H4v16H2v2h20v-2zm-10 0V5h4v14z");
}

</style>
