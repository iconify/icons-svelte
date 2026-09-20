<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j72wbrmpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sip-outline-sharp" {...props}></Icon>
<style>
:global(.j72wbrmpz) {
  fill: currentColor;
  d: path("M11 15h2V9h-2zm3 0h1.5v-2H19V9h-5zm-9 0h5v-3.75H6.5v-.75H10V9H5v3.75h3.5v.75H5zm10.5-3.5v-1h2v1zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
