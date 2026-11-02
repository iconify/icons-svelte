<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5t3-2bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-menu-fill" {...props}></Icon>
<style>
:global(.z5t3-2bqo) {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm14 2H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2m0 4H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2m-8 4a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Z");
}

</style>
