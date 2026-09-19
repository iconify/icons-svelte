<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3rq_2x_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-view-day" {...props}></Icon>
<style>
:global(.t3rq_2x_q) {
  fill: currentColor;
  d: path("M2 21h19v-3H2zM21 8H2v8h19zM2 3v3h19V3z");
}

</style>
