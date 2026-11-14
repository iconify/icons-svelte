<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnhsuco0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:signal-head-two" {...props}></Icon>
<style>
:global(.rnhsuco0l) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.875 3.75h.25q2.123 0 3.624 1.501t1.501 3.624v6.25q0 2.123-1.501 3.624t-3.624 1.501h-.25q-2.123 0-3.624-1.501T6.75 15.125v-6.25q0-2.123 1.501-3.624t3.624-1.501M12 6.5q-2.25 0-2.25 2.25T12 11t2.25-2.25T12 6.5m-2.25 8.75q0 2.25 2.25 2.25t2.25-2.25T12 13t-2.25 2.25");
}

</style>
