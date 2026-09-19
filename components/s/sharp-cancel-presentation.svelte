<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6thokb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-cancel-presentation" {...props}></Icon>
<style>
:global(.f6thokb_c) {
  fill: currentColor;
  d: path("M1 3v18h22V3zm20 16H3V5h18zM9.41 16L12 13.41L14.59 16L16 14.59L13.41 12L16 9.41L14.59 8L12 10.59L9.41 8L8 9.41L10.59 12L8 14.59z");
}

</style>
