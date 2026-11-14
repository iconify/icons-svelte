<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyhhzpbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ruler-kids" {...props}></Icon>
<style>
:global(.nyhhzpbqx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.868 15.889L15.889 3.868a1.5 1.5 0 0 1 2.121 0l2.122 2.122a1.5 1.5 0 0 1 0 2.121L8.111 20.132a1.5 1.5 0 0 1-2.121 0L3.868 18.01a1.5 1.5 0 0 1 0-2.121m1.768-1.768l1.768 1.768M7.757 12l1.061 1.061m1.061-3.182l1.767 1.767M12 7.757l1.061 1.061m1.06-3.182l1.768 1.768");
}

</style>
