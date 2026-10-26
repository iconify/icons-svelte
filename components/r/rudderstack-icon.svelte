<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":258};
const content = `<path class="rg155fb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:rudderstack-icon" {...props}></Icon>
<style>
:global(.rg155fb3o) {
  d: path("M256 0H0c0 136.177 106.017 248.816 241.945 257.057l14.055.852z");
}

</style>
