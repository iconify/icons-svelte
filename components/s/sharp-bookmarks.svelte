<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwzrstbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-bookmarks" {...props}></Icon>
<style>
:global(.jwzrstbgk) {
  fill: currentColor;
  d: path("m19 18l2 1V1H7v2h12zM17 5H3v18l7-3l7 3z");
}

</style>
