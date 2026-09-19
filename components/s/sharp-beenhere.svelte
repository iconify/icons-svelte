<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhey4ubjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-beenhere" {...props}></Icon>
<style>
:global(.jhey4ubjv) {
  fill: currentColor;
  d: path("M3.01 1L3 17l9 6l8.99-6L21 1zM10 16l-5-5l1.41-1.42L10 13.17l7.59-7.59L19 7z");
}

</style>
