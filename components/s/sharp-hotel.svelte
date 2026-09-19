<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1gqquboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-hotel" {...props}></Icon>
<style>
:global(.q1gqquboj) {
  fill: currentColor;
  d: path("M7 13c1.66 0 3-1.34 3-3S8.66 7 7 7s-3 1.34-3 3s1.34 3 3 3m16-6H11v7H3V5H1v15h2v-3h18v3h2z");
}

</style>
