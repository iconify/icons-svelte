<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mowwfmb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:unfold-more-outline" {...props}></Icon>
<style>
:global(.mowwfmb4y) {
  fill: currentColor;
  d: path("m12 21l-4.5-4.5l1.45-1.45L12 18.1l3.05-3.05l1.45 1.45zM8.95 9.05L7.5 7.6L12 3.1l4.5 4.5l-1.45 1.45L12 6z");
}

</style>
