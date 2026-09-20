<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky3gtyq5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:single-bed-outline-sharp" {...props}></Icon>
<style>
:global(.ky3gtyq5k) {
  fill: currentColor;
  d: path("M7 19H6l-.65-2H4v-7h2V5h12v5h2v7h-1.35L18 19h-1l-.65-2h-8.7zm6-9h3V7h-3zm-5 0h3V7H8zm-2 5h12v-3H6zm12 0H6z");
}

</style>
