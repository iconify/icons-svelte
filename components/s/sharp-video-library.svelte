<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iaktu0poq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-video-library" {...props}></Icon>
<style>
:global(.iaktu0poq) {
  fill: currentColor;
  d: path("M4 6H2v16h16v-2H4zm18-4H6v16h16zM12 14.5v-9l6 4.5z");
}

</style>
