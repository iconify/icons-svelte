<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_qvqrwif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:window-outline-sharp" {...props}></Icon>
<style>
:global(.u_qvqrwif) {
  fill: currentColor;
  d: path("M20 20H4V4h16zm-7.5-7.5V19H19v-6.5zm0-1H19V5h-6.5zm-1 0V5H5v6.5zm0 1H5V19h6.5z");
}

</style>
