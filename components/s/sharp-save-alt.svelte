<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlwupcc-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-save-alt" {...props}></Icon>
<style>
:global(.wlwupcc-e) {
  fill: currentColor;
  d: path("M19 12v7H5v-7H3v9h18v-9zm-6 .67l2.59-2.58L17 11.5l-5 5l-5-5l1.41-1.41L11 12.67V3h2z");
}

</style>
