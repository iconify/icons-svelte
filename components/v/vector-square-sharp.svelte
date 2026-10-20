<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1n433bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:vector-square-sharp" {...props}></Icon>
<style>
:global(.a1n433bki) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L7 3L7 7L3 7ZM17 3L21 3L21 7L17 7ZM3 17L7 17L7 21L3 21ZM17 17L21 17L21 21L17 21ZM7 5L17 5M7 19L17 19M5 7L5 17M19 7L19 17");
}

</style>
