<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7jkwjnuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-text-rotate-vertical" {...props}></Icon>
<style>
:global(.c7jkwjnuf) {
  fill: currentColor;
  d: path("M15.75 5h-1.5L9.5 16h2.1l.9-2.2h5l.9 2.2h2.1zm-2.62 7L15 6.98L16.87 12zM6 20l3-3H7V4H5v13H3z");
}

</style>
