<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj5kogb_z"/><path class="f9josw8pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-local-movies" {...props}></Icon>
<style>
:global(.f9josw8pf) {
  fill: currentColor;
  d: path("M20 21V3h-2v2h-2V3H8v2H6V3H4v18h2v-2h2v2h8v-2h2v2zM8 17H6v-2h2zm0-4H6v-2h2zm0-4H6V7h2zm6 10h-4V5h4zm2-12h2v2h-2zm0 4h2v2h-2zm0 6v-2h2v2z");
}

:global(.sj5kogb_z) {
  fill: currentColor;
  d: path("M10 5h4v14h-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
