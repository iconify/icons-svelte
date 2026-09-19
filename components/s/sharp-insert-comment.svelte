<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaun0fbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-insert-comment" {...props}></Icon>
<style>
:global(.oaun0fbwx) {
  fill: currentColor;
  d: path("M22 2H2v16h16l4 4zm-4 12H6v-2h12zm0-3H6V9h12zm0-3H6V6h12z");
}

</style>
