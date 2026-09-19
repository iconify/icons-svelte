<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9ihp5bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-museum" {...props}></Icon>
<style>
:global(.z9ihp5bhr) {
  fill: currentColor;
  d: path("M22 11V9L12 2L2 9v2h2v9H2v2h20v-2h-2v-9zm-6 7h-2v-4l-2 3l-2-3v4H8v-7h2l2 3l2-3h2z");
}

</style>
