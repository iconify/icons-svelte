<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8shq4bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-repeat-one" {...props}></Icon>
<style>
:global(.s8shq4bfo) {
  fill: currentColor;
  d: path("M13 15V9h-1l-2 1v1h1.5v4zm6-2h-2v4H7v-3l-4 4l4 4v-3h12zM17 2v3H5v6h2V7h10v3l4-4z");
}

</style>
