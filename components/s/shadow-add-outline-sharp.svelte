<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n73pcqbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:shadow-add-outline-sharp" {...props}></Icon>
<style>
:global(.n73pcqbpt) {
  fill: currentColor;
  d: path("M13 14v-3h-3V9h3V6h2v3h3v2h-3v3zM2 22V6h4V2h16v16h-4v4zm6-6h12V4H8z");
}

</style>
