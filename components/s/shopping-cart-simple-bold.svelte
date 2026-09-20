<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vczzzuzmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:shopping-cart-simple-bold" {...props}></Icon>
<style>
:global(.vczzzuzmi) {
  fill: currentColor;
  d: path("M241.55 64.74A12 12 0 0 0 232 60H60.23l-8.67-31.21A12 12 0 0 0 40 20H20a12 12 0 0 0 0 24h10.88l34.3 123.49a28.09 28.09 0 0 0 27 20.51H191a28.09 28.09 0 0 0 27-20.51l25.63-92.28a12 12 0 0 0-2.08-10.47m-46.75 96.33A4 4 0 0 1 191 164H92.16a4 4 0 0 1-3.85-2.93L66.9 84h149.31ZM108 220a20 20 0 1 1-20-20a20 20 0 0 1 20 20m104 0a20 20 0 1 1-20-20a20 20 0 0 1 20 20");
}

</style>
