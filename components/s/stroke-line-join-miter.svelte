<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqgrwxbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:stroke-line-join-miter" {...props}></Icon>
<style>
:global(.kqgrwxbyd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21V4C3 3.4477 3.4477 3 4 3H21M11 21V12C11 11.4477 11.4477 11 12 11H21");
}

</style>
