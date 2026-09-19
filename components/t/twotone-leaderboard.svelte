<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex1p-mb-r"/><path class="ymbm-3bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-leaderboard" {...props}></Icon>
<style>
:global(.ex1p-mb-r) {
  fill: currentColor;
  d: path("M10 5h4v14h-4zm-6 6h4v8H4zm16 8h-4v-6h4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.ymbm-3bvm) {
  fill: currentColor;
  d: path("M16 11V3H8v6H2v12h20V11zm-6-6h4v14h-4zm-6 6h4v8H4zm16 8h-4v-6h4z");
}

</style>
