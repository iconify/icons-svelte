<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rociuuvnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:signal-zero-broken" {...props}></Icon>
<style>
:global(.rociuuvnl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20H3.0001");
}

</style>
