<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyq38cc_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:short-text-outline-sharp" {...props}></Icon>
<style>
:global(.zyq38cc_t) {
  fill: currentColor;
  d: path("M5 14.5v-1h8v1zm0-4v-1h14v1z");
}

</style>
