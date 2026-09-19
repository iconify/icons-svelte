<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqc50hzap"/><path class="wokadwdga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-send-to-mobile" {...props}></Icon>
<style>
:global(.gqc50hzap) {
  fill: currentColor;
  d: path("M17 18H7V6h10v1h2V1H5v22h14v-6h-2z");
}

:global(.wokadwdga) {
  fill: currentColor;
  d: path("m22 12l-4-4v3h-5v2h5v3z");
}

</style>
