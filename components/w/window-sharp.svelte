<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amv2avbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:window-sharp" {...props}></Icon>
<style>
:global(.amv2avbbf) {
  fill: currentColor;
  d: path("M13 13h8v8h-8zm0-2V3h8v8zm-2 0H3V3h8zm0 2v8H3v-8z");
}

</style>
