<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk4_z6fiq"/><path class="he_sxxb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-install-mobile" {...props}></Icon>
<style>
:global(.he_sxxb4l) {
  fill: currentColor;
  d: path("m18 14l5-5l-1.41-1.41L19 10.17V3h-2v7.17l-2.59-2.58L13 9z");
}

:global(.hk4_z6fiq) {
  fill: currentColor;
  d: path("M17 18H7V6h7V1H5v22h14v-7h-2z");
}

</style>
