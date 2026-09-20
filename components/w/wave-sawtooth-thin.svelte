<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ted-gmb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wave-sawtooth-thin" {...props}></Icon>
<style>
:global(.ted-gmb0r) {
  fill: currentColor;
  d: path("m234.1 131.41l-104 64a4 4 0 0 1-2.1.59a4 4 0 0 1-4-4V71.16l-97.9 60.25a4 4 0 0 1-4.2-6.82l104-64A4 4 0 0 1 132 64v120.84l97.9-60.25a4 4 0 1 1 4.2 6.82");
}

</style>
