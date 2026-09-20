<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fb757xbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wave-triangle-bold" {...props}></Icon>
<style>
:global(.fb757xbci) {
  fill: currentColor;
  d: path("m241.73 135l-52 72a12 12 0 0 1-19.46 0L76 76.5L33.73 135a12 12 0 1 1-19.46-14l52-72a12 12 0 0 1 19.46 0L180 179.5l42.27-58.5a12 12 0 1 1 19.46 14");
}

</style>
