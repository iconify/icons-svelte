<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4207mbrf"/><path class="i-s8jb5ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-markunread" {...props}></Icon>
<style>
:global(.f4207mbrf) {
  fill: currentColor;
  d: path("M20 6H4l8 5zM4 8v10h16V8l-8 5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.i-s8jb5ba) {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 2l-8 5l-8-5zm0 12H4V8l8 5l8-5z");
}

</style>
