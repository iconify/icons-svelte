<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdeatbb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-airline-seat-legroom-reduced" {...props}></Icon>
<style>
:global(.bdeatbb1f) {
  fill: currentColor;
  d: path("M19.97 21H14v-3l1-4H6V3h6v6h5c1.1 0 2 .9 2 2l-2 7h2.97zM5 15V3H3v14h9v-2z");
}

</style>
