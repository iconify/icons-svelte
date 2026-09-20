<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmj9aab0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-comfy-alt" {...props}></Icon>
<style>
:global(.kmj9aab0w) {
  fill: currentColor;
  d: path("M3 10V3h7v7zm0 11v-7h7v7zm11-11V3h7v7zm0 11v-7h7v7z");
}

</style>
