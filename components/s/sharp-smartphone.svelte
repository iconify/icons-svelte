<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xep23pbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-smartphone" {...props}></Icon>
<style>
:global(.xep23pbiq) {
  fill: currentColor;
  d: path("M5 1v22h14V1zm12 18H7V5h10z");
}

</style>
