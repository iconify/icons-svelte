<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0xmhj-1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:stroke-line-join-round-sharp-fill" {...props}></Icon>
<style>
:global(.v0xmhj-1o) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 22L3 11C3 6.5817 6.5817 3 11 3L22 3M11 22L11 11L22 11");
}

</style>
