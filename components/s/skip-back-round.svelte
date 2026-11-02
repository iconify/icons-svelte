<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kocz6pb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-back-round" {...props}></Icon>
<style>
:global(.kocz6pb7d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15.336 5.504l-6 4c-1.781 1.187-1.781 3.805 0 4.992l6 4C17.33 19.826 20 18.396 20 16V8c0-2.396-2.67-3.825-4.664-2.496M4 5v14");
}

</style>
