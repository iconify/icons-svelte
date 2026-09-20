<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj-zf_bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-comfy-outline-sharp" {...props}></Icon>
<style>
:global(.fj-zf_bna) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm18-9V6H4v5zm-10 7h10v-5H10zm-6 0h4v-5H4z");
}

</style>
