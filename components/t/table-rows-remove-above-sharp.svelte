<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l66sj53zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:table-rows-remove-above-sharp" {...props}></Icon>
<style>
:global(.l66sj53zl) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 4L3 4L3 22L21 22L21 4L18 4M3 13L21 13M8.7071 1.7071L15.2929 8.2929M15.2929 1.7071L8.7071 8.2929");
}

</style>
