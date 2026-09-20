<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_utlo_ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:style-sharp" {...props}></Icon>
<style>
:global(.w_utlo_ao) {
  fill: currentColor;
  d: path("m4.321 20.3l-2.046-.946l2.046-4.389zm2.77-4.377l2.144 5.962H7.09zm4.923 5.408L6.837 7.127l9.446-3.439l5.196 14.185zM11.88 9.713q.287-.288.287-.713t-.287-.712T11.167 8t-.712.288t-.288.712t.288.713t.712.287t.713-.288");
}

</style>
