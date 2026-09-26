<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe5gnfbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:trending-down-sharp-duotone" {...props}></Icon>
<style>
:global(.oe5gnfbqk) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.7071 6.7071L8.5 13.5L13.5 8.5L21.8243 16.8243M15 17L22 17L22 10");
}

</style>
