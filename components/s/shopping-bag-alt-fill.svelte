<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs33i3bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-bag-alt-fill" {...props}></Icon>
<style>
:global(.vs33i3bwv) {
  fill: currentColor;
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm13.685 3.557A4 4 0 0 0 16 8a1 1 0 0 0-2 0a2 2 0 1 1-4 0a1 1 0 0 0-2 0a4 4 0 0 0 3.999 4c1.607 0 3.06-.963 3.686-2.443");
}

</style>
