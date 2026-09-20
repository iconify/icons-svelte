<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oq9hetbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-down-20-filled" {...props}></Icon>
<style>
:global(.oq9hetbzk) {
  fill: currentColor;
  d: path("M11.32 17.215c-.568 1.047-2.071 1.047-2.638 0l-6.5-12a1.5 1.5 0 0 1 1.32-2.213H16.5a1.5 1.5 0 0 1 1.319 2.214z");
}

</style>
