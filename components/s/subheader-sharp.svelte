<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6iva4bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:subheader-sharp" {...props}></Icon>
<style>
:global(.i6iva4bso) {
  fill: currentColor;
  d: path("M6.616 9.192h8v-2h-8zM4 20V4h16v16z");
}

</style>
