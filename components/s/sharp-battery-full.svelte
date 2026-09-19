<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itkj75bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-full" {...props}></Icon>
<style>
:global(.itkj75bfr) {
  fill: currentColor;
  d: path("M17 4h-3V2h-4v2H7v18h10z");
}

</style>
