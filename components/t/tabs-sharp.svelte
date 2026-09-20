<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruwuvqbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tabs-sharp" {...props}></Icon>
<style>
:global(.ruwuvqbjk) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14v-7.615H5zm7-11h6V6h-6z");
}

</style>
