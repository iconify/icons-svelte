<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":171};
const content = `<path class="rk7lmb1sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:tidal-icon" {...props}></Icon>
<style>
:global(.rk7lmb1sc) {
  fill: var(--svg-color--0a0b09, #0a0b09);
  d: path("m128.004 85.339l42.664 42.67l-42.664 42.667l-42.669-42.667zM42.667.002L85.335 42.67L42.667 85.34L0 42.67zm170.666 0L256 42.67l-42.667 42.67l-42.666-42.67l-42.663 42.669l-42.669-42.67L128.004 0l42.663 42.665z");
}

</style>
