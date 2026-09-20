<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="lr4dbbmbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:star-one-quarter-28-filled" {...props}></Icon>
<style>
:global(.lr4dbbmbi) {
  fill: currentColor;
  d: path("m11 7.355l-.99 2.006l-6.017.874A1.45 1.45 0 0 0 2.75 11.68c0 .365.138.735.44 1.03l4.354 4.244l-1.028 5.993c-.108.63.193 1.18.66 1.474c.41.257.946.316 1.444.054L11 23.223z");
}

</style>
