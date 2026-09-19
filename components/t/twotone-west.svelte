<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhj2-jbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-west" {...props}></Icon>
<style>
:global(.rhj2-jbsm) {
  fill: currentColor;
  d: path("m9 19l1.41-1.41L5.83 13H22v-2H5.83l4.59-4.59L9 5l-7 7z");
}

</style>
