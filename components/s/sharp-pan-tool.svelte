<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2oz5gbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-pan-tool" {...props}></Icon>
<style>
:global(.w2oz5gbzg) {
  fill: currentColor;
  d: path("M23 4v20H10.02L1 14.83L2.9 13L8 15.91V3h3v8h1V0h3v11h1V1h3v10h1V4z");
}

</style>
