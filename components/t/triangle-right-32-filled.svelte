<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vwaoxftwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:triangle-right-32-filled" {...props}></Icon>
<style>
:global(.vwaoxftwf) {
  fill: currentColor;
  d: path("M27.317 18.846c2.242-1.235 2.242-4.457 0-5.693L7.82 2.403C5.653 1.21 3 2.777 3 5.25v21.492c0 2.473 2.652 4.04 4.818 2.846z");
}

</style>
