<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_s0d_m8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:video-label-outline-sharp" {...props}></Icon>
<style>
:global(.r_s0d_m8a) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-4h16V6H4z");
}

</style>
