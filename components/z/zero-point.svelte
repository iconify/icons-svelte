<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2mgvi-0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:zero-point" {...props}></Icon>
<style>
:global(.r2mgvi-0b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19m-13-3.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M12 13v4.5");
}

</style>
