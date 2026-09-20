<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uh3x4hb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-justify-20-filled" {...props}></Icon>
<style>
:global(.uh3x4hb5k) {
  fill: currentColor;
  d: path("M2 4.25a.75.75 0 0 1 .75-.75h14.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 4.25m0 5a.75.75 0 0 1 .75-.75h14.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 9.25m.75 4.25a.75.75 0 0 0 0 1.5h14.5a.75.75 0 0 0 0-1.5z");
}

</style>
