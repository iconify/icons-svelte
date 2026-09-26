<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v220aebru"/><path class="dar05kv8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:venus-fill" {...props}></Icon>
<style>
:global(.dar05kv8d) {
  d: path("M12 14L12 22M8.5 19L15.5 19");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v220aebru) {
  fill: currentColor;
  d: path("M19 8C19 11.866 15.866 15 12 15C8.134 15 5 11.866 5 8C5 4.134 8.134 1 12 1C15.866 1 19 4.134 19 8Z");
  stroke: none;
}

</style>
