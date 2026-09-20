<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c1ulpab_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:stool-bold" {...props}></Icon>
<style>
:global(.c1ulpab_a) {
  fill: currentColor;
  d: path("M204 64V40a20 20 0 0 0-20-20H72a20 20 0 0 0-20 20v24a20 20 0 0 0 20 20h2L52.15 222.13a12 12 0 1 0 23.7 3.74L83.1 180h89.8l7.25 45.87a12 12 0 1 0 23.7-3.74L182 84h2a20 20 0 0 0 20-20M76 44h104v16H76Zm93.11 112H86.89l11.36-72h59.5Z");
}

</style>
