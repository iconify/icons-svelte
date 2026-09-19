<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekhohtbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-piano" {...props}></Icon>
<style>
:global(.ekhohtbhu) {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-8 11.5h1.25V19h-4.5v-4.5H11V5h2zM5 5h2v9.5h1.25V19H5zm14 14h-3.25v-4.5H17V5h2z");
}

</style>
