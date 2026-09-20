<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="riyerkbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:unknown-med-outline-sharp" {...props}></Icon>
<style>
:global(.riyerkbte) {
  fill: currentColor;
  d: path("M3 12.5v-2h8v2zm9.98 0v-2h8v2z");
}

</style>
