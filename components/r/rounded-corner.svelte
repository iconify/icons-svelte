<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_3jmkb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:rounded-corner" {...props}></Icon>
<style>
:global(.l_3jmkb6o) {
  fill: currentColor;
  d: path("M3 21v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm0-4V3h2v2zm4 16v-2h2v2zM7 5V3h2v2zm4 16v-2h2v2zm4 0v-2h2v2zm4 0v-2h2v2zm0-4v-2h2v2zm2-4h-2V8q0-1.25-.875-2.125T16 5h-5V3h5q2.075 0 3.538 1.463T21 8z");
}

</style>
