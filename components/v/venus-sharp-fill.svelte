<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v220aebru"/><path class="kixvbiqhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:venus-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.kixvbiqhq) {
  d: path("M12 14L12 23M7.5 19L16.5 19");
}

:global(.v220aebru) {
  fill: currentColor;
  d: path("M19 8C19 11.866 15.866 15 12 15C8.134 15 5 11.866 5 8C5 4.134 8.134 1 12 1C15.866 1 19 4.134 19 8Z");
  stroke: none;
}

</style>
