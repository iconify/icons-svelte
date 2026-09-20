<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="soa8ozaic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-comfy-alt-sharp" {...props}></Icon>
<style>
:global(.soa8ozaic) {
  fill: currentColor;
  d: path("M2 10V2h8v8zm0 12v-8h8v8zm12-12V2h8v8zm0 12v-8h8v8z");
}

</style>
