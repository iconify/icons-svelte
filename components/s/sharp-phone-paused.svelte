<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5pyccc_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-phone-paused" {...props}></Icon>
<style>
:global(.y5pyccc_g) {
  fill: currentColor;
  d: path("M15 3h2v7h-2zm4 0h2v7h-2zm-5.79 14.37a15.05 15.05 0 0 1-6.59-6.59l2.53-2.53L8.54 3H3.03C2.45 13.18 10.82 21.55 21 20.97v-5.51l-5.27-.61z");
}

</style>
