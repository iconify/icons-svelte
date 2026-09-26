<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-s8rx_ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:subtitles" {...props}></Icon>
<style>
:global(.m-s8rx_ul) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 4H19C20.65685 4 22 5.34315 22 7V17C22 18.65685 20.65685 20 19 20H5C3.34315 20 2 18.65685 2 17V7C2 5.34315 3.34315 4 5 4ZM6 10H8M12 10H18M6 14H12M16 14H18");
}

</style>
