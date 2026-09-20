<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xoeeifl5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:tent-thin" {...props}></Icon>
<style>
:global(.xoeeifl5q) {
  fill: currentColor;
  d: path("m251.66 190.38l-64-144A4 4 0 0 0 184 44H72a4 4 0 0 0-3.63 2.35v.06l-64 143.93A4 4 0 0 0 8 196h240a4 4 0 0 0 3.66-5.62M68 66.85V188H14.16ZM76 188V66.85L129.84 188Zm62.6 0L78.16 52H181.4l60.44 136Z");
}

</style>
