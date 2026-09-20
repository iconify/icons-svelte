<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2qr2ukbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:speed-1-75-sharp" {...props}></Icon>
<style>
:global(.e2qr2ukbu) {
  fill: currentColor;
  d: path("M7.73 16.5v-1h1v1zm8.27 0v-1h4v-3h-4v-5h5v1h-4v3h4v5zm-11 0v-8H3v-1h3v9zm6.27 0l2-8H9.307v-1h5.03v.946l-2.03 8.054z");
}

</style>
