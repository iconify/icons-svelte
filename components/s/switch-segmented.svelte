<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs1m195ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:switch-segmented" {...props}></Icon>
<style>
:global(.rs1m195ms) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 5.75H6.875q-2.123 0-3.624 1.501T1.75 10.875v2.25q0 2.123 1.501 3.624t3.624 1.501h10.25q2.123 0 3.624-1.501t1.501-3.624v-2.25q0-2.123-1.501-3.624T17.125 5.75");
}

</style>
