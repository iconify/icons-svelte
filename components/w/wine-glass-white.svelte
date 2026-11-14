<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9hz4ubwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:wine-glass-white" {...props}></Icon>
<style>
:global(.e9hz4ubwe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h11V7a5.5 5.5 0 0 1-11 0Zm5.5 10v9m-4.5 0h9M6.5 7h11");
}

</style>
