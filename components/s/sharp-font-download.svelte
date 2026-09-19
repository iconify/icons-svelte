<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f32noebsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-font-download" {...props}></Icon>
<style>
:global(.f32noebsn) {
  fill: currentColor;
  d: path("M9.93 13.5h4.14L12 7.98zM22 2H2v20h20zm-6.05 16.5l-1.14-3H9.17l-1.12 3H5.96l5.11-13h1.86l5.11 13z");
}

</style>
