<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhl8kcbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:trending-flat" {...props}></Icon>
<style>
:global(.fhl8kcbfh) {
  fill: currentColor;
  d: path("m22 12l-4-4v3H3v2h15v3z");
}

</style>
